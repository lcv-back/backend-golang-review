# Kiến thức về Golang

## I> Cấu trúc và Quản lý Bộ Nhớ

1. Trong Golang, khi nào bạn sử dụng pointers và khi nào không nên sử dụng pointers? Lợi ích của việc sử dụng pointers là gì?

2. Golang sử dụng garbage collection để quản lý bộ nhớ. Bạn có thể giải thích cách mà garbage collector hoạt động trong Golang và làm thế nào nó ảnh hưởng đến hiệu suất của ứng dụng?

## II> Concurrency và Parallelism

1. Bạn có thể giải thích sự khác biệt giữa concurrency và parallelism trong Golang không? Khi nào bạn sẽ sử dụng concurrency thay vì parallelism?

2. Làm thế nào để xử lý race conditions trong Golang? Bạn có thể giải thích về **sync.Mutex** và **sync.RWMutex** và sự khác biệt của chúng không?

3. Bạn có thể giải thích cách sử dụng **select** statement trong Golang và khi nào nó hữu ích trong việc quản lý nhiều channel?

## III> Channel và Goroutine

1. Channel trong Golang là gì và tại sao chúng lại quan trọng trong việc xử lý đồng thời? Bạn có thể mô tả cách bạn đã sử dụng channel trong một dự án thực tế?

2. Bạn có thể mô tả sự khác biệt giữa buffered channel và unbuffered channel trong Golang không? Trong trường hợp nào bạn sẽ sử dụng mỗi loại?

3. Bạn đã từng sử dụng channel với goroutines để giải quyết các bài toán về đồng thời chưa? Nếu có, bạn có thể cho ví dụ về cách bạn đã sử dụng chúng?

## IV> Error Handling

1. Trong Golang, cách xử lý lỗi có sự khác biệt lớn so với các ngôn ngữ khác. Bạn có thể giải thích tại sao Golang lại sử dụng cơ chế trả về lỗi thay vì exceptions?

2. Bạn có thể mô tả cách bạn sử dụng **defer**, **panic**, và **recover** trong Golang không? Trong tình huống nào bạn sẽ sử dụng mỗi cái?

## V> Interface và Polymorphism

1. Golang không có kế thừa trực tiếp như các ngôn ngữ khác. Thay vào đó, Golang sử dụng interfaces. Bạn có thể giải thích cách interfaces hoạt động trong Golang và tại sao chúng lại mạnh mẽ?

2. Bạn có thể cho một ví dụ về khi nào bạn sử dụng interface trong Golang để thực hiện polymorphism?

## VI> Structs và Methods

1. Bạn có thể giải thích sự khác biệt giữa types trong Golang như struct và interface không? Khi nào bạn nên sử dụng một cái hơn cái kia?

2. Làm thế nào bạn định nghĩa và sử dụng methods trong Golang? Bạn có thể cho một ví dụ về việc sử dụng method receiver (pointer receiver và value receiver) trong Golang?

## VII> Go Routine và Channel Patterns

1. Bạn có thể giải thích các patterns phổ biến khi sử dụng Goroutine và Channel trong Golang để xử lý các bài toán đồng thời như fan-out, fan-in, hoặc worker pool không?

2. Bạn đã bao giờ sử dụng context trong Golang để kiểm soát sự đồng bộ và timeout chưa? Bạn có thể mô tả cách sử dụng context trong một ứng dụng thực tế?

## VIII> Performance Optimization

1. Bạn làm thế nào để tối ưu hiệu suất của ứng dụng Golang trong các tình huống có tải cao? Có những công cụ hoặc kỹ thuật nào bạn thường sử dụng để đo lường và cải thiện hiệu suất của ứng dụng Golang?

2. Golang hỗ trợ concurrency rất tốt, nhưng có những vấn đề nào mà bạn cần phải lưu ý khi làm việc với các hệ thống nhiều luồng và yêu cầu hiệu suất cao?

## IX> Testing trong Golang

1. Bạn có thể giải thích cách viết unit test trong Golang không? Bạn sẽ tổ chức các test case như thế nào để kiểm tra các chức năng backend của bạn?

2. Làm thế nào để mock một interface trong Golang khi bạn muốn kiểm tra một phần của mã mà không cần gọi đến các dịch vụ bên ngoài?

## X> Tối ưu hóa và Quản lý Đoạn Code Lớn

1. Làm thế nào để bạn quản lý và tối ưu mã nguồn trong các ứng dụng Golang lớn? Bạn có chiến lược gì để giữ mã nguồn dễ hiểu và dễ bảo trì khi phát triển các hệ thống phức tạp?

2. Bạn có thể chia sẻ về cách sử dụng các design patterns trong Golang để làm cho mã nguồn của bạn dễ duy trì hơn?
