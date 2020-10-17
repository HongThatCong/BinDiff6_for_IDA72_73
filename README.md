# BinDiff6_for_IDA72_73
BinDiff6 và BinExport11 cho IDA 72, 72 user.
Yêu cầu: phải có Java JDK hay JRE đã install. Lên trang của Oracle mà down, install.

# HD cài đặt
1. Unzip = 7zip, chép hết các dll vào IDA\plugins hay vào %IDA user dir%\plugins

2. Chép hết thư mục Fonts vào Windows\Fonts

3. Chép thư mục BinDiff gồm các exe và cmd, xml file vào đâu đó. 

Vd tui thường để ở thư mục IDA\tools cho các tools liên quan đến IDA.

4. Mở bindiff.xml, chỉnh lại các đường dẫn "ui directory=" và "ida directory=" cho đúng với thư mục BinDiff chứa .jar file và thư mục IDA

Nhớ là không có / hay \ cuối, bug của họ đó, hành mệt nghỉ đó.

5. Copy file bindiff.xml đã sữa vào thư mục C:\Users\%USERNAME%\AppData\Roaming\BinDiff

Ra ngoài cmd, chạy thử bindiff_ui.cmd xem JDK và JRE install đúng không, lên được GUI không.

Done

# HD Sử dụng:
Xem ở https://www.zynamics.com/bindiff/manual/

# Notes:
Dùng chung BinDiff và Diaphora khi diff. 

Diff nhiều thì sẽ có kinh nghiệm, nhớ hàm, nhớ code, nhớ thư viện, lib...

Chân chọng, bét rì ga
