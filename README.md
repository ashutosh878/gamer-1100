<!DOCTYPE html>
<html>
<head>

<meta charset="utf-8" />
<title>Untitled</title>
<style>
@import url("https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css");

h1 {
	text-align: center;
	margin: 35px 0 20px 0 !important;
}</style>
<script src="http://dabblet.com/code/prefixfree.min.js"></script>
<script>
if (parent === window) {
	document.addEventListener('DOMContentLoaded', function() {
		// alert('Hello world!');		
	});
}
</script>
</head>
<body><div class="container">
    <h1>FormSubmit Demo</h1>
    <form target="_blank" action="https://formsubmit.co/your@email.com" method="POST">
        <div class="form-group">
            <div class="form-row">
                <div class="col">
                    <input type="text" name="name" class="form-control" placeholder="Full Name" required>
                </div>
                <div class="col">
                    <input type="email" name="email" class="form-control" placeholder="Email Address" required>
                </div>
            </div>
        </div>
        <div class="form-group">
            <textarea placeholder="Your Message" class="form-control" name="message" rows="10" required></textarea>
        </div>
        <button type="submit" class="btn btn-lg btn-dark btn-block">Submit Form</button>
    </form>
</div></body>
</html>
