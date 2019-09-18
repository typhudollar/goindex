![GoIndex](https://raw.githubusercontent.com/donwa/goindex/master/themes/logo.png)  
  

## Demo  
material: [https://index.gd.workers.dev/](https://index.gd.workers.dev/)  
classic: [https://indexc.gd.workers.dev/](https://indexc.gd.workers.dev/)  

## Cài đặt RCLONE  
1.Cài đặt phần mềm `rclone`
2.Làm theo các bước hướng dẫn từ trang [https://rclone.org/drive/]( https://rclone.org/drive/) để build một file cấu hình
3.Thực thi lệnh `rclone config file` để tìm đường dẫn file cấu hình `rclone.conf`  
4.Mở `rclone.conf`,tìm các giá trị của các `root_folder_id` and `refresh_token`  
5.Tải index.js tại https://github.com/donwa/goindex và điền các giá trị tương ứng trong file index.js  
6.Dán đoạn code vào [Cloudflare Workers](https://www.cloudflare.com/)
