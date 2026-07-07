<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Budget Optimizer | AI Project Impact Simulator</title>
    <style>
        body {
            font-family: "Segoe UI", Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f6f9;
            color: #333;
        }

        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.2em;
        }

        header p {
            margin: 5px 0 0;
            font-size: 1.1em;
        }

        .map-container {
            margin: 24px auto 18px;
            max-width: 320px;
            text-align: center;
        }

        .map-container img {
            width: 100%;
            max-width: 220px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            display: block;
            margin: 0 auto;
        }

        .map-container p {
            margin-top: 10px;
            font-weight: bold;
            color: #555;
            font-size: 0.95rem;
        }

        .project-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin: 30px auto;
            max-width: 800px;
        }

        .btn {
            padding: 14px 24px;
            border: none;
            border-radius: 8px;
            background-color: #e9ecef;
            cursor: pointer;
            font-size: 16px;
            transition: all 0.3s ease;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .btn:hover {
            background-color: #007bff;
            color: white;
            transform: translateY(-2px);
        }

        .cta-btn {
            display: block;
            margin: 40px auto;
            padding: 14px 28px;
            border: none;
            border-radius: 8px;
            background-color: #28a745;
            color: white;
            cursor: pointer;
            font-size: 18px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .cta-btn:hover {
            background-color: #218838;
        }

        footer {
            background-color: #f1f1f1;
            text-align: center;
            padding: 15px;
            font-size: 14px;
            color: #555;
            margin-top: 50px;
            border-top: 1px solid #ddd;
        }
    </style>
</head>

<body>
    <!-- Header -->
    <header>
        <h1>ALLOC AID</h1>
        <p>Helping MPs visualize project impact in their constituencies</p>
    </header>

    <!-- Constituency Map -->
    <div class="map-container">
        <img src="logo.jpeg" alt="Constituency Map">
        <p>Select your constituency</p>
    </div>

    <!-- Project Selection -->
    <div class="project-buttons">
        <a href="hospital.html">
            <button class="btn">🏥 Hospital</button>
        </a>
        <a href="phc.html">
            <button class="btn">🏪 PHC</button>
        </a>
        <a href="road.html">
            <button class="btn">🛣️Road</button>
        </a>
        <a href="watertank.html">
            <button class="btn">🚰 Water Tank</button>
        </a>
        <a href="school.html">
            <button class="btn">🏫 School</button>
        </a>
    </div>
    <footer>
        Built for Madurai For Nation Hackathon | Powered by Google Cloud
    </footer>
</body>

</html>
