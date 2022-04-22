<header class="container">
	<nav>
		<a href="/" class="home">Shortly</a>
		<ul>
			<li><a href="/features">Features</a></li>
			<li><a href="/Pricing">Pricing</a></li>
			<li><a href="/Resources">Resources</a></li>
		</ul>
	</nav>
	<div class="account-links">
		<a href="/login">Login</a>
		<a href="/signup">Sign Up</a>
	</div>
</header>

<style>
    header {
        display: flex;
        justify-content: space-between;
    }
    .home {
        font-weight: var(--font-light);
        font-size: calc(var(--font-size) * 2);
    }
    nav { display: flex; }
	a { 
		text-decoration: none; 
		color: var(--color-gray);
	}
	.home { color: var(--color-very-dark-voilet); }
	ul {
		list-style-type: none;
		margin: 0;
        display: flex;
        gap: 1rem;
	}
	li { margin: 0; }
    .account-links {
        display: flex;
        gap: 1rem;
    }
</style>