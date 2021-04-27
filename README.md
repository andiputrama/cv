<html>
<head>
	 <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl" crossorigin="anonymous" />

    <!-- Bootstrap Icons -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css" />

    <!-- My CSS -->
	<style type="text/css">
	.jumbotron {
	padding-top: 6rem;
	background-color: #e2edff;
	}
	
	#projects {
	background-color: #e2edff;
	}
	
	section {
	padding-top: 5rem;
	}
	</style>
	
    <title>Andi Putrama</title>
    <link href='https://fonts.googleapis.com/css?family=Open+Sans' rel='stylesheet' type='text/css'>
    <script type="text/javascript" src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script>
    $(document).ready(function(){
        $("#home").click(function(){
            $("body").animate({ scrollLeft: 0},"slow");
        });
        $("#about").click(function(){
            $("body").animate({ scrollLeft: 1500},"slow");
        });
        $("#contact").click(function(){
            $("body").animate({ scrollLeft: 3000},"slow");
        });
    });
    </script>
    <style>
        body{
            overflow-x:hidden;
            font-family: 'Open Sans', sans-serif;
        }
        h1 {
            padding-left: 30px;
        }
        #container{
            position:absolute;
            top:0;
            left:0;
            width:4500;
            height:100%;
        }
        .content{
            width:1500;
            height:100%;
            float:left;
        }
        .home{
            background-color:#ffffff;
        }
        .about{
            background-color:#c9fdff;
		}
        .sekolah{
            background-color:#e4ffdb;
        }
        .contact{
            background-color:#e2edff;
        }

        .link {
            padding: 0 5px;
            color: #ffffff;
        }
    </style>
</head>
<body >
	<!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary shadow-sm fixed-top">
      <div class="container">
        <a class="navbar-brand" href="#">Andi Putrama</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">About</a>
            </li>
			<li class="nav-item">
              <a class="nav-link" href="#sekolah">Sekolah</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- Akhir Navbar -->
    
    <div id="container">
        <div class="content home" id="home">
            <h1>Home</h1>
		<!-- Jumbotron -->
    <section class="jumbotron text-center">
      <img src="https://drive.google.com/file/d/0B0ZABn0wQjUudHVycC1MdG9Ib2xTRTZ3dWljRlBVcWZZcWpV/view?usp=sharing" alt="" width="200" class="rounded-circle img-thumbnail" />
      <h1 class="display-4">Hi. I'm Andi putrama</h1>
    </section>
    <!-- Akhir Jumbotron -->
        </div>
        <div class="content about" id="about">
            <h1>About Me</h1>
		<!-- About -->
    <section id="about">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>About Me</h2>
          </div>
        </div>
        <div class="row justify-content-center fs-5 text-center">
          <div class="col-md-4">
            <p>Nama saya Andi Putrama, biasa di panggil andi. saya mahasiswa semester 4 di universitas singa perbangsa karawang (UNSIKA)</p>
          </div>
          <div class="col-md-4">
            <p>saya lahir pada tanggal 4 juli 2001. sekarang saya tinggal di bogor. mungkin cukup sekian perkenalan dari saya</p>
          </div>
        </div>
      </div>
    </section>
    <!-- Akhir About -->
		<div class="content sekolah" id="sekolah">
            <h1>Riwayat Sekolah</h1>
		<!-- Sekolah -->
    <section id="sekolah">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>Riwayat Sekolah</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="img/projects/1.jpg" class="card-img-top" alt="Project 1" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="img/projects/2.jpg" class="card-img-top" alt="Project 2" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="img/projects/4.jpg" class="card-img-top" alt="Project 4" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="img/projects/5.jpg" class="card-img-top" alt="Project 5" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Akhir Projects -->
        </div>
        </div>
        <div class="content contact" id="contact">
            <h1>Contact</h1>
		<!-- Contact -->
    <section id="contact">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>Contact Me</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-md-6">
            <div class="alert alert-success alert-dismissible fade show d-none my-alert" role="alert">
              <strong>Terimakasih!</strong> Pesan anda sudah kami terima.
              <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
            </div>
            <form name="my-contact-form">
              <div class="mb-3">
                <label for="name" class="form-label">Nama Lengkap</label>
                <input type="text" class="form-control" id="name" aria-describedby="name" name="nama" />
              </div>
              <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="email" aria-describedby="email" name="email" />
              </div>
              <div class="mb-3">
                <label for="pesan" class="form-label">Pesan</label>
                <textarea class="form-control" id="pesan" rows="3" name="pesan"></textarea>
              </div>
              <button type="submit" class="btn btn-primary btn-kirim">Kirim</button>

              <button class="btn btn-primary btn-loading d-none" type="button" disabled>
                <span class="spinner-border spinner-border-sm" role="status" aria-hidden="true"></span>
                Loading...
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>
    <!-- Akhir Contact -->
        </div>
    </div>
	
	
</body>
</html>
