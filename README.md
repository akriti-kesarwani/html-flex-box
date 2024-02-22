# html-flex-box

body{
    direction:ltr
}
    .flex-container{
        display: -webkit-flex;
        display:flex;
        /* -webkit-flex-direction:row-reverse;
        flex-direction:row-reverse; */

        /* -webkit-flex-direction:column-reverse;
        flex-direction:column-reverse;
        -webkit-flex-direction:column;
        flex-direction:column;  */

        /* -webkit-justify-content:flex-end;
        justify-content: flex-end; */

        /* -webkit-justify-content:space-between;
        justify-content:space-between; */

/* align-items property  */
        /* -webkit-align-items: stretch;
        align-items: stretch;  */

        /* -webkit-align-items: start;
        align-items: start;   */

        /* -webkit-align-items:end;
        align-items:end;  */

        /* -webkit-align-items:center;
        align-items:center; */

        /* -webkit-align-items: baseline;
        align-items: baseline; */

        -webkit-flex-wrap: wrap;
        flex-wrap: wrap;

        width:1000px;
        height:1100px;
        /* height: auto; */
        background-color:rgb(236, 228, 16);
    }
    .flex-item{
        background-color: rgb(236, 79, 11);
        width:300px;
        height:300px;
        margin:30px;
    }
    .flex-item1{
        background-color: rgb(74, 118, 78);
        width:300px;
        height:300px;
        margin:30px;
    }
    .flex-item2{
        background-color: rgb(11, 187, 236);
        width:300px;
        height:300px;
        margin:30px;
    }
    .flex-item3{
        background-color: rgb(165, 17, 17);
        width:300px;
        height:300px;
        margin:30px;
    }
    .flex-item4{
        background-color: rgb(60, 11, 236);
        width:300px;
        height:300px;
        margin:30px;
    }





html code



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Example</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="flex-container">
        <div class="flex-item">I thrive on challenge and constantly set goals for myself, so I have something to strive towards. I am not comfortable with settling, and I am always looking for an opportunity to do better and achieve greatness. In my previous role, I was promoted three times in less than two years.</div>
        <div class="flex-item1">I thrive on challenge and constantly set goals for myself, so I have something to strive towards. I am not comfortable with settling, and I am always looking for an opportunity to do better and achieve greatness. In my previous role, I was promoted three times in less than two years.</div>
        <div class="flex-item2">I thrive on challenge and constantly set goals for myself, so I have something to strive towards. I am not comfortable with settling, and I am always looking for an opportunity to do better and achieve greatness. In my previous role, I was promoted three times in less than two years.</div>
        <div class="flex-item3">I thrive on challenge and constantly set goals for myself, so I have something to strive towards. I am not comfortable with settling, and I am always looking for an opportunity to do better and achieve greatness. In my previous role, I was promoted three times in less than two years.</div>
        <div class="flex-item4">I thrive on challenge and constantly set goals for myself, so I have something to strive towards. I am not comfortable with settling, and I am always looking for an opportunity to do better and achieve greatness. In my previous role, I was promoted three times in less than two years.</div>
    </div>
</body>
</html>
