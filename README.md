<!DOCTYPE html>
<html>
<head>
    <title>My Profile Card</title>
    <style>
        body{
            background-color: white;
            font-family: 'Times New Roman', Times, serif;

        }
        .avatar {
            width: 100px;
            height: 100px;
            align-items: center;
            border-radius: 70%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            background-color: aliceblue;
        }
        .title {
            font-size: 24px;
            font-weight: bold;
            color: #333;
            margin: auto;
        }
        .name {
            font-size: 18px;
            color: #3292ffad;
            margin-bottom: auto
        }
        .description {
            color: #666666bb;
            margin: auto
        }
        .card {
            width: 400px;
            height: 250px;
            background-color: white;
            margin:auto;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;

            display: flex;
            flex-direction: column;
            align-items: center;    
            gap: 6px;
        }
        .button{
            display: inline-block;
            padding: 10px 20px;
            background: linear-gradient(to right, #4CAF50, #45a049);
            color:white;
            border-radius: 15px;
            transition: 0.3s;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            margin-top: auto

        }
        .button:hover {
            background-color: linear-gradient(to right, #45a049, #4CAF50);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
            transform: scale(1.2);
        }
    </style>
</head>
<body>
    <div class="card">
        <img class="avatar" src="https://scontent.fsgn7-2.fna.fbcdn.net/v/t39.30808-1/656711395_1629860861474339_7425911904000737896_n.jpg?stp=dst-jpg_s200x200_tt6&_nc_cat=102&ccb=1-7&_nc_sid=1d2534&_nc_ohc=u1NrNSvg4P0Q7kNvwFBruLH&_nc_oc=AdoBffIGLdtzl-j8wUIF08-TyAk1sXUBXOQQgBaCfmrjBlqLDbQxq9HS7BY-p6UTA62vreL-ViC4Uvga-uGJpRDR&_nc_zt=24&_nc_ht=scontent.fsgn7-2.fna&_nc_gid=Jhf29B9twGHZdw8Dy4URwA&_nc_ss=7a3a8&oh=00_Af0DdFm9TxaeeAh2-9NEcAasCLLr1SYEyHwLxrYE9ceAsg&oe=69DA4C94" alt="Avatar">
        <h2 class="name">Trần Phú Quí</h2>
        <p class="description">i want to be a great developer</p>
        <a href="https://www.facebook.com/qui.phu.478953678/" class="button"> Contact Me</a>

    </div>

</body>
</html>
