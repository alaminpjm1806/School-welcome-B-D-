<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our School</title>
    <style>
        /* CSS code */
        .slider {
            display: flex;
            overflow: hidden;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            position: relative; /* Added */
        }

        .slider img {
            width: 100%;
            animation: slide 15s infinite;
        }

        @keyframes slide {
            0% { transform: translateX(0); }
            20% { transform: translateX(-100%); }
            40% { transform: translateX(-200%); }
            60% { transform: translateX(-100%); }
            80% { transform: translateX(0); }
            100% { transform: translateX(-100%); }
        }
    </style>
</head>
<body>
    <header>
        <!-- Header content -->
    </header>

    <nav>
        <!-- Nav content -->
    </nav>

    <div class="container">
        <section id="home">
            <h2>Welcome</h2>
            <div class="slider">
                <img src="https://via.placeholder.com/1200x400/0d47a1/ffffff?text=Welcome+to+Our+School" alt="Welcome to Our School">
                <img src="https://via.placeholder.com/1200x400/1976d2/ffffff?text=High+Quality+Education" alt="High Quality Education">
                <img src="https://via.placeholder.com/1200x400/0d47a1/ffffff?text=Join+Us+Today" alt="Join Us Today">
            </div>
        </section>
    </div>
    <footer>
        <!-- Footer content -->
    </footer>
</body>
</html>
