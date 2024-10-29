<!DOCTYPE html>
<html lang="vi">
    <head>
        <meta charset="UTF-8">
        <meta  name="viewport" content="width=device-width, initial-scale=1">
         <title>Web cua anh vu</title>
        <link href="main.css" rel="stylesheet">
    </head>
    <style>
        body{
            font-family: 'Arial',sans-serif;
            background-color: rgb(213, 209, 247);
            /*cursor: url("https://emoji.discadia.com/emojis/e6b54c74-5cb8-47b9-be2e-f4a9be1dd207.png"),auto;*/
        }
        .nenchu{
            padding: 20px;
            text-align: center;
        }
        .color{
            color: white;
        }
        div{
            margin: 20px ;
            padding: 20px;
            background-color: rgb(139, 167, 243);
            border-radius: 10px;
            transition: transform 0.25s;
            box-shadow:0 10px 100px rgba(0, 0, 0, 0.1);
        }
        .button{
            padding: 20px;
            background-color: rgb(139, 167, 243);
        }
        div:hover {
            transform: scale(1.05); /* x1,05*/
        }
        .vitriimg{
            position: absolute;
            top: 20px;
            right:20px;
        }
        .vitriimg img{ /* do lon + hinh dang img */
            width: 100px;
            height: 100px;
            border-radius: 100%;
        }
        .nen1{
            background: url("https://img3.thuthuatphanmem.vn/uploads/2019/06/13/anh-nen-anime-dep_095240141.jpg" );
            padding: 20px;
            text-align: center;
        }
        .nen2{
            background: none;
        }
    </style>
    <body>
        <div class="vitriimg">
            <img src="https://i.pinimg.com/564x/6e/c1/5c/6ec15c97237bfb99e09fe80f2690df4d.jpg" alt="Hình đại diện" />
        </div>
        <div class="nen1">
            <h1 class="color">
                NGUYỄN TRỌNG ANH VŨ
            </h1>
            <p class="color">
                Lớp: 10 Tin <br>
                Trường THPT Chuyên Hà Tĩnh 
            </p>
        </div>
        <div>
            <h2>
                Mô tả cá nhân :
            </h2>
            <li >Chăm chỉ</li>
            <li >Hài hước </li>
            <li>Ngại giao tiếp</li>
            <li>Coder</li>
            <li>Wibu</li>
        </div>
        <div >
            <h2>Sở thích của bản thân</h2>
            <li>Lập trình</li>
            <li>xem phim</li>
            <li>nghe nhạc</li>
            <li>chơi cờ vua</li>
            <li>tìm tòi và khám phá thứ mới</li>
        </div>
        <div>
            <li>create by: ANH VU</li>
            <li>Email: anhvu07062009@gmail.com</li>
            <li>Facebook: <a href="https://www.facebook.com/profile.php?id=100075000543516">NGUYEN TRONG ANH VU</a></li>
        </div>
        <div class="nen1">
            <h2>Bạn có nhận xét gì về trang web này</h2>
        <form id="form">
            <input type="text" placeholder="gửi phản hồi" required />
            <button type="submit">Gửi phản hồi </button>
        </form>
        <h2>Ước gì được đánh giá 10/10</h2>
        <h2>muốn có thêm tg up web lỏd này </h2>
        <img src="https://i.pinimg.com/564x/41/0e/f3/410ef37a6d5e709449fb8c887bc9e0dd.jpg">
        </div>
    </body>
</html>
