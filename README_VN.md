# 3.0-GC

Tải 2 files dưới trước khi bắt đầu  <br>
https://download.oracle.com/java/17/archive/jdk-17.0.3.1_windows-x64_bin.exe<br>
https://www.mongodb.com/try/download/compass<br>
https://www.mongodb.com/try/download/community<br>

## Cài đặt Server

1: Vào link https://github.com/lassedds/3.0-GC/releases/tag/Release và tải GC3.0 trong mục Release.

2: Tải file resources trong link này: https://github.com/lassedds/3.0-Resources

3: Đặt file resources trong folder 3.0 GC // Nhớ đổi tên folder thành "resources" để file hoạt động.

4: Chuột phải vào file start_config.cmd và nhấp vào **Edit**. Tiếp theo, tìm folder "*bin*" của phiên bản java đã cài đặt. Nó sẽ nằm trong đường dẫn **`C:\Program Files\Java\`**, tiếp tục mở folder "*jdk-17.x.x.x*". Copy đường dẫn từ folder "*bin*". Đường dẫn được copy sẽ trông như sau: **`C:\Program Files\Java\jdk-17.x.x.x\bin\`**. Sau đó, copy đường dẫn vào dòng lệnh "*JAVA_PATH =*" trong file *start_config.cmd*.

5: Cài đặt xong, mở file *start.bat* để khởi động Server.

6: Bây giờ, vào thư mục Genshin 3.0 và đặt file <a href="https://drive.google.com/file/d/1esXUB4Q_Y_wDjvqnNbN8jiQUKsO11N1S/view?usp=sharing"> này </a> vào cả hai thư mục sau: <br>
1. "*YOURGENSHINFOLDER/GenshinImpact_Data/Managed/Metadata*"<br>
2. "*YOURGENSHINFOLDER/GenshinImpact_Data/Native/Data/Metadata*"

## Hướng dẫn cài Fiddler

1: Tải xuống Fiddler classic <a href=https://www.telerik.com/download/fiddler> tại đây </a>.

2: Khi mở Fiddler Classic, chọn mục **Tools** ở đầu Fiddler và nhấp vào **Options**.

3: Trong menu **Options**, sẽ có rất nhiều menu phụ. Tìm tới dòng **HTTPS**. Chọn mục **HTTPS** và nhấp vào hộp nhỏ bên cạnh dòng chữ "*Decrypt HTTPS traffic*".

4: Sau bước thứ 4, đừng đóng menu **Options** mà chuyển tiếp đến menu con **Connections**. Trong menu con **Connections**, tìm mục "*Fiddler Classiclistens onport*". Theo mặc định, port sẽ là '8888'. Port có thể **change** thành bất kỳ số gì khác, bài viết sử dụng 8080.

5: Bây giờ chọn mục **OK** trong menu **Options** và tìm nút **FiddlerScript**. Chọn mục đó và copy script <a href=https://github.lunatic.moe/fiddlerscript>here</a>. Paste script vừa chọn vào Fiddler thay thế script cũ, lưu ý nhớ chọn **Save Script** trước khi thoát.

6: Giờ đã có thể chạy game nhưng chưa xong. Sau khi thử và đăng nhập, một số thông báo sẽ hiện trong Fiddler và chỉ cần xác nhận tất cả.

7: Thành công! Fiddler đã được ngon lành. 10 điểm nỗ lực! Nếu bạn có bất kỳ câu hỏi nào, hãy join <a href=https://discord.gg/AYtB7Q2er8>Discord</a> của chúng tôi