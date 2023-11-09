I, GIT
- Version Control (kiểm soát phiên bản)
- Một hệ thống ghi chú lại tất cả các hoạt động trên dự án
- Dùng GIT để quay loại bất cứ thời điểm nào của dự án để check lại code của mình

II, GITHUB
- Là dịch vụ cloud để đẩy dự án lên trên mạng.
- Cho phép làm việc chung với nhau và kiểm soát được người nào đang làm gì trên dự án

III, Các từ khóa trong GITHUB
- Repository (Thư mục dự án // Kho)
- Branch (Cành): mặc định là main hoặc master
- Conflict (xung đột)
- Local
- Remote

# Commmands

-git init: sẽ làm dự án hoặc repository của chúng ta, trở thành git repository
(có nghĩa là dự án của chúng ta có thể sử dụng được GIT)

-git status: kiểm tra trạng thái của dự án.

-git add {tên file}: chuẩn bị lưu lại thời điểm hiện tại của dự án.
-> 'git add .' : để lưu lại tất cả file trong dự án.

-git reset: Trong trường hợp đổi ý muốn lấy ra file chuẩn bị lưu.

-git commit: chính thức lưu file trong dự án.
-> git commit -m 'ghi chú'

-git log: xem lại những thời điểm đã lưu trong dự án
-> Gọn hơn: git log --oneline

-git checkout {id của commit}: quay lại thời điểm bạn mong muốn.

-git checkout {branch name}: quay lại thời điểm hiện tại

-git branch: kiểm tra xem đang ở cành nào.

-git checkout -b {branch}: tạo branch mới

-git merge {branch}: gộp chung lại branch B vào branch A (thực hiện lệnh trên branch A)

-git branch -d {branch name}: xóa đi một branch

IV, Kết hợp GIT và GITHUB
- Đẩy dữ liệu dự án lên GITHUB, là ta đẩy các dữ liệu từ local lên remote
- Local: tất cả các dữ liệu trên máy tính của chúng ta (code, hình ảnh, video,...)

# Commands:
-git push {link REMOTE repo} {branch name}: Đẩy local repository lên remote repository trên GITHUB

-git remote add origin {link REMOTE repo}: tạo đường hướng dẫn tên là origin ( cách sử dụng alios)

-Sau khi đã tạo được alios, dùng lệnh sau để push dự liệu lên remote repository:
git push {alios} {branch name}

-Lấy một remote repo về local:
1.Mở cmd
2.Gõ: cd {đường dẫn folder chứ dự án}
3.Gõ: git clone {Đường dẫn GITHUB}
4.Gõ: cd {tên thư mục}
5.Gõ: code . (để mở dự án lên)
-> Nếu dự án được kéo về kiểu này thì ko cần điền alios khi push dự án lên remote.
Chỉ cần gõ: git push là đủ.

-Trường hợp tạo branch ở local, thì làm cách nào để đẩy branch này lên remote repo?
git push -u {origin} {branch name}