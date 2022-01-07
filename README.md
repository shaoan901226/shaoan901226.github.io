# 九九乘法表
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title></title>
    <style>
        table {
            border: 1px solid black;
            border-collapse: collapse;
            background-color: #4846c7;
        }

        th {
            background-color: #109ef0;
        }
        td,th {
            border: 1px solid black;
            font-family: 微軟正黑體;
            padding: 5px;
            text-align:center;
        }

            td:hover {
                background-color: #109ef0;
            }
    </style>
</head>
<body>
    <script>
        document.write("<table>");
        document.write("<tr>");
            for (a = 2; a < 10; a++) {
                document.write("<th>");
                document.write(a + "的乘法表" + "<br>");
                document.write("</th>");
            }
        document.write("</tr>");
        for (x = 2; x < 10; x++) {
            document.write("<td>");
            for (y = 1; y < 10; y++) {
                document.write(x + "*" + y + "=" + x * y + "<br>");
            }
            document.write("</td>");
        }
        document.write("</table>");
    </script>
</body>
</html>
