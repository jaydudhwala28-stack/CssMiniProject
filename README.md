* {
    margin: 0;
    padding: 0;
    font-family: "Google Sans", sans-serif;

}

.main_box {
    background-image: url("photo.jpg");
    height: 100vh;
    background-size: cover;
}

.btn_one i {
    font-size: 21px;
    font-weight: 100px;
    position: absolute;
    left: 16px;
    line-height: 60px;
    cursor: pointer;
    transition: all 0.2s linear;


}

.sidebar_menu {
    position: fixed;
    left: -300px;
    height: 100vh;
    width: 300px;
    background-color: rgba(255, 255, 255, 0.1);
    box-shadow: 0 0 6px rgba(255, 255, 255, 0.9);
    border-radius: 6px;
    transition: all 0.3s linear;

}

.sidebar_menu .logo {
    position: absolute;
    width: 100px;
    line-height: 60px;
    box-shadow: 0 0 4px rgba(255, 255, 255, 0.9);
    height: 60px;
    width: 300px;
    border-radius: 6px;
}

.sidebar_menu .logo a {
    color: wheat;
    left: 50px;
    position: fixed;
    text-decoration: none;
    font-weight: 500px;
    font-size: 21px;
    opacity: 0.8;
    transition: all 0.3s linear;

}

.sidebar_menu .menu {
    color: white;
    position: absolute;
    width: 100%;
    top: 85px;
}

.sidebar_menu .btn_two i {
    font-size: 20px;
    line-height: 20px;
    position: absolute;
    left: 282px;
    margin-top: 2px;
    color: rgba(247, 245, 245, 0.4);
    cursor: pointer;
    transition: all 0.2s linear;
}

.sidebar_menu .menu li {
    margin-top: 9px;
    padding: 14px 20px;
    opacity: 0.6;
    font-size: 22px;
}

.sidebar_menu .menu i,
a {
    color: white;
    text-decoration: none;
    font-size: 20px;

}

.sidebar_menu .menu i {
    padding-right: 10px;
}

.sidebar_menu .social_media {
    opacity: 0.5;
    position: absolute;
    margin-top: 800px;
    margin-left: 6px;
    left: 25%;
    bottom: 200px;
}

.sidebar_menu .social_media i {
    padding: 0 4px;

}

#check {
    display: none;
}

.sidebar_menu .menu li:hover {
    box-shadow: 0 0 4px rgba(255, 255, 255, 0.9);
    border-radius: 25px;
    opacity: 1;
    font-size: 26px
}

.btn_one i:hover {
    font-size: 25px;
}

.btn_two i:hover {
    font-size: 24px;
    opacity: 1;
}

.sidebar_menu .social_media i:hover {
    font-size: 26px;
    transform: scale(1.1);

}

#check:checked~.sidebar_menu {
    left: 0;
}

#check:checked~.btn_one i {
    opacity: 0;
}

.sidebar_menu .logo a:hover {
    opacity: 1;
    font-size: 22px
}
