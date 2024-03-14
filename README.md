<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styyle.css">
</head>
<body>
<div class="div">
    <div class="nav">
        <div class="nav1">
            lobe
        </div>
        <div class="nav2">
           <ul>Overview</ul>
           <ul>Example</ul>
           <ul>Tour</ul>
           <ul>Blog</ul>
           <ul>Help</ul>
        </div>
        <div class="nav3">
            <button>Download</button>
        </div>
    </div>
    <div class="content">
        <div class="conupper">
            <div class="lobe">Lobe</div>
            <div class="Tour">Tour</div>
        </div>
        <div class="msg">
            <h1>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate odit consequuntur dolorem magnam voluptatem sequi id voluptas, ratione perferendis accusamus.
            </h1>
        </div>
        <div class="conmid">
<img src="https://images.unsplash.com/photo-1705323111381-681f06e96675?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="image">
        </div>
        <div class="conlover">
            <div class="lover1">Train our app</div>
            <div class="lover2">with Lobe</div>
            <div class="nav3">
                <button>Download</button>
            </div>
        </div>
    </div>
    <div class="foder">
        <div class="line1">
            <h1>lobe</h1>
            <ul>Lorem ipsum dolor sit.</ul>
            <ul>Lorem ipsum dolor sit amet.</ul>
            <ul>Lorem ipsum dolor sit amet consectetur.</ul>
        </div>
        <div class="line2">
            <h1>About</h1>
            <ul>Download</ul>
            <ul>Overview</ul>
            <ul>Example</ul>
            <ul>Blog</ul>
        </div>
        <div class="line3">
            <h1>General</h1>
            <ul>Notice</ul>
            <ul>License</ul>
            <ul>Press inquiries</ul>
            <ul>Press images</ul>
        </div>
        <div class="line4">
            <h1>Resources</h1>
            <ul>Help</ul>
            <ul>Tour</ul>
            <ul>Content</ul>
            <ul>Privecy</ul>
        </div>
        <div class="line5"></div>
    </div>
</div>
   
</body>
</html>
//css//
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.nav{
    padding: 10px;
    display: flex;
    justify-content: space-between;
}

.nav1{
    font-size: 30px;
}

.nav2{
    padding-top: 10px;
    display: flex;
    gap: 20px;
}

.nav3 button{
    color: rgba(252, 250, 250, 0.945);
   background-color: aqua;
   border: 10px solid aqua;
   border-radius: 20px;
}

.conupper{
    padding-top: 50px;
    display: flex;
    justify-content: center;
    gap: 10px;
    
}

.lobe{
    font-size: 50px;
}

.Tour{
    color: aqua;
    font-size: 50px;
}

.content h1{
    padding: 0 100px;
}

.content{
    padding: 0 100px;
}

.conmid{
    height: 700px;
    width: 100%;
    background-color: rgb(172, 166, 166);
    border-radius: 30px;
    display: flex;
    justify-content: center;
    padding-top: 50px;
    margin-top: 100px;
}

.conmid img{
    height: 600px;
    border-radius: 30px;
    
}

.conlover{
    margin: 100px 0 0 450px;
    
}

.lover1{
    font-size: 50px;
    
}

.lover2{
    font-size: 50px;
    
}

.conlover .nav3{
    margin-left: 13%;
    padding: 30px;
}

.foder{
    display: flex;
    padding: 0 100px;
    justify-content: space-between;
}

.foder .line1{
    gap: 200px;
}
# project7
