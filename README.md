<!DOCTYPE html>
<html>
<head>
    <title>RCB Players - Bootstrap</title>

    <!-- Bootstrap CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<div class="container mt-4">

    <!-- Heading -->
    <h3 class="text-center">RCB Players</h3>
    <p class="text-center">Bootstrap Grid and Flex Example</p>

    <!-- GRID SYSTEM -->
    <h5 class="mt-4">Grid System</h5>

    <div class="row text-center">
        <div class="col-12 col-md-4 border p-2">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSHkz-CtfvMGgRgdHNQsxEMfsV37rycmXyYn4jbyBlVnEZZ-edxrgDlTl1Rbfo6teEkc2zsRuzlDUSc71RWUp5JtoegBcvnZPuUMwRmkDw&s=10"
                 class="img-fluid" alt="Virat Kohli">
            <p>Virat Kohli</p>
        </div>

        <div class="col-12 col-md-4 border p-2">
            <img src="https://img1.hscicdn.com/image/upload/f_auto/lsci/db/PICTURES/CMS/320000/320068.6.jpg"
                 class="img-fluid" alt="padikkal">
            <p>padikkal</p>
        </div>

        <div class="col-12 col-md-4 border p-2">
            <img src="https://images.financialexpressdigital.com/2018/04/IPL-2018-9.jpg?quality=100"
                 class="img-fluid" alt="ABD">
            <p>ABD</p>
        </div>

        <div class="col-12 col-md-4 border p-2">
            <img src="https://media.crictracker.com/media/attachments/1685394467279_Glenn-Maxwell.jpeg"
                 class="img-fluid" alt="Glenn Maxwell">
            <p>Glenn Maxwell</p>
        </div>
    </div>

    <!-- FLEX SYSTEM -->
    <h5 class="mt-4">Flexbox</h5>

    <div class="d-flex flex-column flex-md-row border p-2 text-center">
        <div class="p-2 border">RCB</div>
        <div class="p-2 border">IPL Team</div>
        <div class="p-2 border">Bangalore</div>
    </div>

    <!-- Footer -->
    <div class="text-center mt-4">
        <p>Created using Bootstrap</p>
    </div>

</div>

</body>
</html>
