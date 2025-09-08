<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>চৌধুরী’স শপ - Online Store</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">চৌধুরী’স শপ</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link active" href="#">হোম</a></li>
        <li class="nav-item"><a class="nav-link" href="#products">পণ্য</a></li>
        <li class="nav-item"><a class="nav-link" href="#order">অর্ডার</a></li>
      </ul>
    </div>
  </div>
</nav>

<header class="text-center p-5 bg-light">
  <h1>স্বাগতম চৌধুরী’স শপ এ!</h1>
  <p>আপনার প্রিয় পণ্য অর্ডার করুন অনলাইনে</p>
</header>

<main class="container my-5">

  <section id="products">
    <h2 class="mb-4 text-center">আমাদের পণ্যসমূহ</h2>
    <div class="row row-cols-1 row-cols-md-3 g-4">

      <!-- Product 1 -->
      <div class="col">
        <div class="card h-100">
          <img src="assets/product1.jpg" class="card-img-top" alt="Product 1">
          <div class="card-body">
            <h5 class="card-title">পণ্য ১</h5>
            <p class="card-text">দাম: ৫০০ টাকা</p>
            <a href="#order" class="btn btn-primary">অর্ডার করুন</a>
          </div>
        </div>
      </div>

      <!-- Product 2 -->
      <div class="col">
        <div class="card h-100">
          <img src="assets/product2.jpg" class="card-img-top" alt="Product 2">
          <div class="card-body">
            <h5 class="card-title">পণ্য ২</h5>
            <p class="card-text">দাম: ৭৫০ টাকা</p>
            <a href="#order" class="btn btn-primary">অর্ডার করুন</a>
          </div>
        </div>
      </div>

      <!-- Product 3 -->
      <div class="col">
        <div class="card h-100">
          <img src="assets/product3.jpg" class="card-img-top" alt="Product 3">
          <div class="card-body">
            <h5 class="card-title">পণ্য ৩</h5>
            <p class="card-text">দাম: ১০০০ টাকা</p>
            <a href="#order" class="btn btn-primary">অর্ডার করুন</a>
          </div>
        </div>
      </div>

    </div>
  </section>

  <section id="order" class="my-5">
    <h2 class="mb-4 text-center">অর্ডার ফর্ম</h2>
    <form action="https://formspree.io/f/yourformid" method="POST" class="mx-auto" style="max-width:500px;">
      <div class="mb-3">
        <label for="name" class="form-label">আপনার নাম</label>
        <input type="text" class="form-control" id="name" name="name" required>
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">ইমেইল</label>
        <input type="email" class="form-control" id="email" name="_replyto" required>
      </div>
      <div class="mb-3">
        <label for="product" class="form-label">পছন্দের পণ্য</label>
        <select class="form-select" id="product" name="product" required>
          <option value="পণ্য ১">পণ্য ১</option>
          <option value="পণ্য ২">পণ্য ২</option>
          <option value="পণ্য ৩">পণ্য ৩</option>
        </select>
      </div>
      <div class="mb-3">
        <label for="quantity" class="form-label">পরিমাণ</label>
        <input type="number" class="form-control" id="quantity" name="quantity" min="1" required>
      </div>
      <button type="submit" class="btn btn-success w-100">অর্ডার পাঠান</button>
    </form>
  </section>

</main>

<footer class="text-center py-4 bg-primary text-white">
  © ২০২৫ চৌধুরী’স শপ
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
