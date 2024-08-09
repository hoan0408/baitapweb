<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    body
    {
        background-color: black;
        color: white;
        display: flex;
        height: 100vh;
        align-items: center;
        justify-content: center;
        margin: 0;
        font-size: 16px;
        font-family: Arial;
    }
    .project
    {
        background-color: #222;
            width: 320px;
            padding: 20px;
            border-radius: 10px;
            text-align: start;
    }
    h2{
        margin-top :0;
        margin-bottom: 2px;
    }
    p
    {
        margin-top: 0;
        margin-bottom: 20px;
        color: grey;
        font-size: 13px;
    }
    .name1
    {
        margin-bottom: 15px;
    }
    .name2
    {
        margin-bottom: 15px;
    }
    .form1 label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
    .form1 input{
            width: 94%;
            padding: 8px;
            border: 1px solid #444;
            border-radius: 5px;
            background-color: #333;
            color: #fff;
            font-size: 14px;
        }
    .form1 select
    {
        width: 100%;
        padding:8px;
        border-radius: 5px;
        border: 1px solid #444;
        background-color: #333;
        color: #fff;
    }
    

    .enter {
            display: flex;
            justify-content: space-between;
        }
    .deploy
    {
        color:black;
        background-color: white;
        height: 35px;
        border-radius: 8px;
        width: 30%;
        border: none;
    }
    .deploy:hover {
            background-color: #c9bcbc;
        }

    .cancel {
            background-color: #555;
            color: white;
            border-radius: 5px;
            height: 35px;
            width: 30%;
            border: none;
          
        }
</style>
<body>
    <div class = "project">
        <h2> Create project
        </h2>
        <p>Deploy your new project in one-click.</p>
        <form >
            <div class = "name1">
               <label for="name" >Name </label><br>
               <input type="text" id="name" name="name" placeholder="Name of your project"> <br>
            </div>
            <div class="name2">
                <label for="framework">Framework</label> <br>
                <select name="framework" id="framework">
                    <option value="">Select</option>
                    <option value="framework1">A</option>
                    <option value="framework2">B</option>
                </select>
            </div>
            <div class="enter">
                <button type="button" class="cancel">Cancel</button>
                <button type="submit" class="deploy">Deploy</button>
            </div>
        </form>
    </div>
</body>
</html>
