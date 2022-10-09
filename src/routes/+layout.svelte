<script>
import '../app.css';
</script>

<div class="app">

	<div class="fixed-top">
		<nav class="navbar navbar-fixed navbar-expand-lg px-3">
		
			<a class="navbar-brand" href="/">Team Avatars</a>

			<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
			</button>

			<div class="collapse navbar-collapse" id="navbarSupportedContent">
				<ul class="navbar-nav mx-auto mb-2 mb-lg-0">
					<li class="nav-item">
						<a class="nav-link" href="#styles">Styles</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="#how-it-works">How it works</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="#pricing">Pricing</a>
					</li>
				</ul>
			</div>

			<ul class="navbar-nav mb-2 mb-lg-0">
				<li class="nav-item ms-6">
					<a class="nav-link btn btn-primary text-light" href="#pricing">Start a project</a>
				</li>
			</ul>
		</nav>
	</div>

	<div style="min-height: 80vh">
		<slot></slot>
	</div>

	<footer style="background-color: #e2e8f0">
		<div class="container p-2">
			<div class="row">
				<div class="col my-2">
					Made by <a href="https://laye.red" target="_blank">Layered</a> &middot; <a href="https://www.instagram.com/yogatella/" target="_blank">@yogatella</a>
				</div>
				<div class="col text-end my-1">
					<a href="mailto:denisa@yogatella.com?subject=Custom team avatars" target="_blank">Contact us</a>
				</div>
			</div>
		</div>
	</footer>
</div>
