
# LESSON 01
## Tinh Thần Học
1. *Học chủ động:*
    - Chủ động tìm hiểu (search gg) trước khi đặt câu hỏi
    - Chủ động sync up vấn đề với mentor để xắp xếp lớp
    - Chủ động đặt câu hỏi khi không hiểu bài 

2. *Học Chăm chỉ:*
    - Làm bài tập đầy đủ trước mỗi buổi học 

3. *Học thông minh:*
    - Luôn hệ thống kiến thức bài học đầy đủ trước khi làm bài tập 

## Công cụ học 
1. *GG classroom*

2. *Zoom*

3. *Playwright - Type script*

    - Playright là 1 **Framework**, ra đời vào năm 2020, verson mới nhất hiện tại là 1.50.0
    
    - **Ưu điểm: **
        - Hỗ trợ nhiều trình duyệt, platform
        - Auto-wait
        - Web-first assertion
        - Tracing
        - Code-gen
    
    - **Tại sao?**
        - Cú pháp đơn giản, hiện đại
        - Dễ học, dễ tiếp cận => giảm rào cản
        

## Cài đặt Tools

1. **NVM**
    - **Node verson manager** - công cụ quản lí các phiên bản Node js
    - **Node js** - công cụ chạy code
    - Cài thông qua VNM => dễ chuyển đổi nhiều phiên bản của Node js
    
    - Cài đặt VNM:
        - On Mac: brew install nvm 
        - On Window: https://github.com/coreybutler/nvm-windows/releases
        
    - Cài đặt Node: 
        - nvm install v22.9.0
        - nvm use v22.9.0
    
2. **Git & Github**
    - Cài đặt Git: https://git-scm.com/download
    
    - **Cấu hình Git:**
        - **Config username:**
           ```git config --global user.name “Phong”```
        - **Config email:**
            ```git config --global user.email “dominhphong306@gmail.com”```
        - **Config branch default:**
            ```git config --global init.defaultBranch main```

    - Tài khoản Github:
        - Đặt tên lịch sự, không nên chứa năm sinh
        - Có avatar để tăng tính chuyên nghiệp, có sự đồng nhất giữa các profile
        
3. **Visual studio code:**

4. **Kết nối Github:**
    - SSH key:
        - Cặp khoá:
            - id_rsa: cần giữ bí mật
            - id_rsa.pub: có thể gửi cho người khác
        - Giúp xác thực đăng nhập dễ dàng hơn
        - Lưu tại ``` ~/.ssh```
        - Tạo SSH key:
            ```ssh-keygen -t rsa -b 4096 -C "your_email@example.com"```
        - Lấy nội dung ssh key: 
            ```cat ~/.ssh/id_rsa.pub```
        - Truy cập: https://github.com/settings/ssh/new để thêm ssh key

## Playwright & the 1st test

1. **1st test:**
    - Tạo Folder: pw-course 
    - Chạy lệnh: ```npm init playwright@latest```
    - Đi tới file: ```example.spec.ts ```
    - Click run test

2. **Đưa code lên GitHub**
    - Tạo repo
    - Khởi tạo :
        - Khởi tạo repo local: ```git init -m "init project"```
        - Liên kết repository vừa tạo: ```git remote add origin <ssh_link>```
        - Thêm code: ```git add```
        - Thêm commit: ```git commit```
    - Push code
        ```git push origin main```
    - Invite Collaborators



    - 