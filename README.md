<br />
<p align="center">

<h3 align="center">ElainaBot</h3>

<p align="center">
    This is a Messenger Bot made by Zeew.
    <br />
    <br />
    <a href="https://github.com/ElainaPr0ject/elaina/issues">Report Bug</a>
    ·
    <a href="https://github.com/ElainaPr0ject/elaina/pulls">Request Feature</a>
    </p>
</p>

<p align="center">
	<img alt="size" src="https://img.shields.io/github/repo-size/ElainaPr0ject/elaina.svg?style=flat-square&label=size">
	<a href="https://github.com/ElainaPr0ject/elaina/commits"><img alt="commits" src="https://img.shields.io/github/commit-activity/m/ElainaPr0ject/elaina?label=commit&style=flat-square"></a>
	
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
    <summary>Table of Contents</summary>
    <ol>
        <li><a href="#introduce">Introduce</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#contributing">Contributing</a></li>
        <li><a href="#license">License</a></li>
        <li><a href="#contact">Contact</a></li>
    </ol>
</details>

<!-- ABOUT THE PROJECT -->
## Introduce
<p><strong>ELAINAPR0JECT LÀ GÌ?</strong></p>
<br />
<p>
<strong>ElainaPr0ject</strong> là một dự án Messenger mang đến cho người 1 trải nghiệm thú vị, mới mẻ. Dự án này được được tạo chủ yếu hỗ trợ cho Group Messenger và được phát triển bởi <strong>Zeew</strong> (Tất nhiên rồi, bạn cũng có thể là 1 người phát triển của nó!).
</p>



<!-- INSTALLATION -->
## Installation

Sau đây là các bước cơ bản để có thể cài đặt và vận hành.

### Yêu cầu

- Dung lượng của máy phải trống tầm 1-2gb.
- Một phần mềm Text Editor.
- Cần hiểu cơ bản về Nodejs và Javascript.
- Một tài khoản Facebook dùng để làm bot (Vì project sử dụng 1 API bên thứ 3 nên nó có thể khiến cho tài khoản Facebook của bạn bị khóa bất cứ lúc nào).
- Cần cài Nodejs, Git - Không cần thiết (và JRE hoặc JDK dành cho phiên bản Java).

### Cài Đặt

#### Windows

1. Tải về [Nodejs](https://nodejs.org/en/) sau đó cài đặt
    1. Nếu bạn window 7 trở xuống và không thể cài đặt nodejs thì có thể tải file cài đặt nodejs-13 [tại đây](https://nodejs.org/download/release/v13.14.0/) nhưng phiên bản nodejs-13 có thể không tương thích với project nên bạn có thể cài bản [Binary 
](https://nodejs.org/en/download) (Không ổn định)

2. Download source code của bot
   1. Clone bằng Git
      1. Chuột phải ở folder cần cài đặt source code nhấn vào git bash
      2. Nhập:
         ```sh
         git clone https://github.com/ElainaPr0ject/Elaina.git
         ```
      
    3. Download trên Github
       1. Truy cập vào [Project](https://github.com/ElainaPr0ject/Elaina)
       2. Chọn vào phần <> Code
       3. Chọn Download Zip
       4. Giải nén file vừa tải vào folder cần cài đặt

3. Cài đặt các package cần thiết
    1. Mở cmd/terminal ở thư mục bot, LƯU Ý thư mục đó phải có file package.json
    2. Nhập:
   ```sh
    npm install
   ```

4. Chỉnh sửa file config
    1. Mở file .env bằng 1 Text Editor
    2. Tùy chỉnh BOTNAME, PREFIX, API_KEY, ...
    3. Sao lưu và đóng lại

5. Lấy appstate
    - Bạn có thể lấy fbstate bằng [c3c-fbstate](https://github.com/c3cbot/c3c-fbstate), nhưng cần đổi tên lại thành appstate.json
      
6. Chạy bot và tận hưởng
    1. Nhập:
       1. Đối với Java
          Xem hướng dẫn tại đây
       3. Đối với Nodejs
          npm start
          hoặc
          node .
    2. Đợi source code load file và tận hưởng!

#### Linux/ubuntu

1. Cài đặt node và git bằng cách nhập vào terminal
   ```sh
    sudo apt-get install curl
    curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash -
    sudo apt-get install nodejs git sqlite3 -y
    sudo npm install -g npm
   ```

3. Clone source code của bot bằng cách nhập vào terminal
   ```sh
    git clone https://github.com/ElainaPr0ject/Elaina.git
   ```

5. Cài đặt các package cần thiết
    1. Mở cmd/terminal ở thư mục bot, LƯU Ý thư mục đó phải có file package.json
    2. Nhập
   ```sh
    npm install
   ```

7. Chỉnh sửa file config
    1. Mở file .env bằng 1 Text Editor
    2. Tùy chỉnh BOTNAME, PREFIX, API_KEY, ...
    3. Sao lưu và đóng lại

8. Lấy appstate
    - Bạn có thể lấy fbstate bằng [c3c-fbstate](https://github.com/c3cbot/c3c-fbstate), nhưng cần đổi tên lại thành appstate.json
    
9. Chạy bot và tận hưởng
    1. Nhập:
       1. Đối với Java
          Xem hướng dẫn tại đây
       3. Đối với Nodejs
          npm start
          hoặc
          node .
    2. Đợi source code load file và tận hưởng!

#### Video hướng dẫn cài đặt

1. Windows: [Comming Soon...]()
2. Linux: [Comming Soon...]()
3. Android: [Comming Soon...]()


<!-- CONTRIBUTING -->
## Contributing

Hy vọng các bạn sẽ thích Project này và hãy fork nó về
Điều này sẽ là 1 động lực to lớn để mình có thể phát triển nó

<!-- LICENSE -->
## License

This project is licensed under the GNU General Public License v3.0 License - see the [LICENSE](LICENSE) file.

<!-- CONTACT -->
## Contact

Zeew - [Facebook](https://www.facebook.com/1000x71021834010) - [GitHub](https://github.com/vudung2008) - [Youtube](https://www.youtube.com/@vudung2008)
