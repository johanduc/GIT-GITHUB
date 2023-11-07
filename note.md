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
