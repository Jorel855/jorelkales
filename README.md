<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jorel Kales - Estratega de Marketing Digital</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet" />
  <style type="text/tailwindcss">
    body {
      font-family: 'Inter', sans-serif;
      background-color: #f8fafc;
    }
    .gradient-bg {
      background: linear-gradient(to right, #6366f1, #8b5cf6);
    }
    .btn-primary {
      @apply bg-indigo-600 text-white px-6 py-3 rounded-lg shadow-lg hover:bg-indigo-700 transition duration-300 ease-in-out;
    }
    .card {
      @apply bg-white rounded-xl shadow-md p-6 transform hover:scale-105 transition duration-300 ease-in-out;
    }
    .input-field {
      @apply w-full p-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-indigo-500;
    }
  </style>
  <style>
    @keyframes fadeInMoveUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .animate-fade-in-up {
      animation: fadeInMoveUp 0.8s ease-out forwards;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .animate-fade-in {
      animation: fadeIn 1s ease-out forwards;
    }
    @keyframes bounceIn {
      0%, 20%, 40%, 60%, 80%, 100% {
        transition-timing-function: cubic-bezier(0.215, 0.61, 0.355, 1);
      }
      0% { opacity: 0; transform: scale3d(0.3, 0.3, 0.3); }
      20% { transform: scale3d(1.1, 1.1, 1.1); }
      40% { transform: scale3d(0.9, 0.9, 0.9); }
      60% { opacity: 1; transform: scale3d(1.03, 1.03, 1.03); }
      80% { transform: scale3d(0.97, 0.97, 0.97); }
      100% { opacity: 1; transform: scale3d(1, 1, 1); }
    }
    .animate-bounce-in {
      animation: bounceIn 1s;
    }
    .loader {
      border: 4px solid #f3f3f3;
      border-top: 4px solid #6366f1;
      border-radius: 50%;
      width: 30px;
      height: 30px;
      animation: spin 1s linear infinite;
      display: none;
      margin: 0 auto;
    }
    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
  </style>
</head>
<body class="text-gray-800">
  <!-- Contenido completo insertado aquí -->
</body>
</html>
