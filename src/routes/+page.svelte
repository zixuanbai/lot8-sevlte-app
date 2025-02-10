<script>
    const navItems = ["Find a Property", "Find Agents", "News", "Commercial"];
</script>

<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #fff;
    }
    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 1rem 2rem;
        border-bottom: 1px solid #ddd;
    }
    nav .logo {
        font-size: 1.5rem;
        font-weight: bold;
    }
    .nav-buttons {
        display: flex;
        gap: 1.5rem;
    }
    .nav-buttons a {
        text-decoration: none;
        padding: 0.5rem 1rem;
        border: 1px solid #ccc;
        border-radius: 4px;
        color: #333;
        font-weight: bold;
        background-color: #fff;
        transition: background-color 0.3s ease, color 0.3s ease;
    }
    .nav-buttons a:hover {
        background-color: #007bff;
        color: #fff;
    }
    .hero {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 4rem 2rem;
    }
    .hero .text {
        max-width: 50%;
    }
    .hero .text h1 {
        font-size: 2.5rem;
        font-weight: bold;
        margin-bottom: 1rem;
    }
    .hero .text p {
        font-size: 1.2rem;
        margin-bottom: 2rem;
    }
    .hero .text input {
        width: 80%;
        padding: 0.8rem;
        border: 1px solid #ddd;
        border-radius: 8px;
        font-size: 1rem;
    }
    .hero .image {
        max-width: 40%;
    }
    .hero .image img {
        width: 100%;
        border-radius: 12px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
</style>

<nav>
    <div class="logo">Lot 8</div>
    <div class="nav-buttons">
        <a href="/agent-signup">AGENT SIGN UP</a>
        <a href="/developer-signup">DEVELOPER SIGN UP</a>
        <a href="/user-signup">USER SIGN UP</a>
        <a href="/signin">SIGN IN</a>
    </div>
</nav>

<section class="hero">
    <div class="text">
        <h1>Australia’s Real Estate Lifestyle Platform</h1>
        <p>Navigate your property journey with ease. Simplifying your search.</p>
        <input type="text" placeholder="Search suburb, postcode or type" />
    </div>
    <div class="image">
        <img src="/images/sydney_skyline.jpg" alt="Featured Property" />
    </div>
</section>




