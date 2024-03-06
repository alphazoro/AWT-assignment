# AWT-assignment
SOCIAL MEDIA PLATFORM


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <title>Social Media Platform</title>
    <style>
        body {
            background-image: url('https://source.unsplash.com/random/1600x900/?nature,technology');
            background-size: cover;
            background-position: center;
            color: #fff;
            font-family: 'Open Sans', sans-serif;
        }
        .card {
            background-color: rgba(255, 255, 255, 0.1);
            border: none;
            box-shadow: 0 16px 32px 0 rgba(0, 0, 0, 0.2);
        }
        .card-img-top {
            width: 100%;
            height: 15vw;
            object-fit: cover;
            border-radius: 5px;
        }
        .card-body {
            padding: 20px;
        }
        .card-title {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }
        .card-text {
            font-size: 0.9rem;
            margin-bottom: 20px;
        }
        .btn-floating {
            position: relative;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 64px;
            height: 64px;
            line-height: 1.875;
            text-align: center;
            vertical-align: middle;
            border-radius: 32px;
            margin: 5px;
            font-size: 24px;
            transition: all 0.3s ease;
        }
        .btn-floating:hover {
            transform: translateY(-2px);
            box-shadow: 0 16px 32px 0 rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="row">
            <div class="col-md-4">
                <div class="card mb-4">
                    <img src="https://via.placeholder.com/150" class="card-img-top" alt="User Profile">
                    <div class="card-body">
                        <h5 class="card-title text-primary">User Name</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="btn btn-primary btn-block">Go to profile</a>
                    </div>
                </div>
            </div>
            <div class="col-md-8">
                <div class="card">
                    <div class="card-body">
