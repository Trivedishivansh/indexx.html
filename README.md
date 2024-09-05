*{
    margin: 0;
    padding: 0;
}

.main{
    width:100%;
    background: url(download.jpg);
    background-position: center;
    background-size: cover;
    height: 100vh;
    position: relative;
    font-family: sans-serif;
}


.navbar{
    width: 86%;
    display: flex;
    margin: auto;
    padding: 15px 0;
    align-items: center;
    justify-content: space-between;
}
.navbar .logo{
    width: 160px;
    cursor: pointer;
    margin-top: -3%;
    margin-left: -2%;

}
ul{
    margin-top: -4%;
}
ul li{
    list-style: none;
    display: inline-block;
    padding: 10px 16px;

}

ul li a{
    font-size: 16px;
    font-weight: bold;
    text-decoration: none;
    color: darkslategray;
    margin-top: -3%;
    transition: .4s ease;


}
ul li a:hover{
    color: rgb(230,104,59);
}
.info{
    margin-left: 7%;
    margin-top: 6%;
}
.info h1{
    font-size: 65px;
    color:rgb(36, 32,30);
}

.info h3{
    font-size: 18px;
    letter-spacing: 1px;
    line-height: 24px;
}
.info span{
    color: rgb(230,104,59);
}
.info a{
    text-decoration: none;
    color: white;
    background: black;
    margin: 26px 0;
    padding: 10px 18px;
    border-radius: 10px;
    display: inline-block;
    transition: .4s ease;

}

.info a:hover{
    background: rgb(59,174,209);
}
