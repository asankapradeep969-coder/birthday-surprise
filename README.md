<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Love ❤️</title>

<style>
*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

body{
    font-family:Arial,sans-serif;
    background:#08030a;
    color:white;
    overflow-x:hidden;
}

/* PASSWORD */
#lockScreen{
    position:fixed;
    inset:0;
    z-index:9999;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:25px;
    background:
        radial-gradient(circle at center,#5b174c,#08030a 70%);
}

.lockBox{
    width:100%;
    max-width:390px;
    padding:35px 25px;
    border-radius:28px;
    background:rgba(255,255,255,.08);
    border:1px solid rgba(255,255,255,.18);
    backdrop-filter:blur(15px);
    box-shadow:0 0 50px rgba(255,20,130,.25);
}

.lockIcon{
    font-size:60px;
    margin-bottom:15px;
}

.lockBox h1{
    font-size:28px;
    margin-bottom:12px;
}

.lockBox p{
    color:#ddd;
    line-height:1.6;
    margin-bottom:25px;
}

input{
    width:100%;
    padding:15px;
    border:0;
    outline:0;
    border-radius:30px;
    text-align:center;
    font-size:16px;
    margin-bottom:15px;
}

button{
    border:0;
    border-radius:30px;
    padding:15
