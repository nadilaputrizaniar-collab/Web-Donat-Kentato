# Web-Donat-Kentato
Web
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kentato XII-H Kel-9 - Donat Kentang Paling Hype!</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
        .hero-bg {
            background-color: #FFF7E0; /* A warm, inviting yellow */
            background-image: radial-gradient(#FFD180 1px, transparent 1px);
            background-size: 20px 20px;
        }
        .btn {
            transition: all 0.3s ease;
        }
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
        }
        .card:hover {
            transform: scale(1.03);
            transition: transform 0.3s ease-in-out;
        }
        /* Custom modal styles */
        .modal {
            transition: opacity 0.3s ease;
        }
    </style>
</head>
<body class="bg-yellow-50">

    <!-- Main Container -->
    <div class="container mx-auto max-w-4xl p-4 sm:p-8">

        <!-- Header Section -->
        <header role="banner" class="text-center p-8 rounded-3xl hero-bg shadow-lg mb-12">
            <h1 class="text-5xl md:text-6xl font-extrabold text-orange-500 tracking-tight">Kentato</h1>
            <p class="text-lg font-semibold text-gray-600 mt-1">XII-H Kelompok 9</p>
            <p class="text-xl md:text-2xl mt-4 text-gray-800 font-semibold">Donat Kentang Paling <span class="text-orange-500">Hype</span> di Sekolah!</p>
            <p class="mt-4 text-gray-700 max-w-2xl mx-auto">
                Pusing sama pelajaran? Butuh <em>mood booster</em>? Kenalin nih, Kentato! Donat kentang super empuk yang manisnya pas, nggak lebay! Cocok banget buat nemenin kamu pas istirahat, ngemil bareng geng, atau dibawa pulang.
            </p>
        </header>

        <!-- Product Variants Section -->
        <section id="varian" role="region" aria-labelledby="varian-title">
            <h2 id="varian-title" class="text-3xl font-bold text-center mb-8 text-gray-800">Pilih Varian Favoritmu!</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                
                <!-- Card 1: Donat Gula Halus -->
                <div class="card bg-white rounded-2xl shadow-md overflow-hidden p-6 text-center">
                    <img src="download.jfif" alt="Donat bolong dengan taburan gula halus" class="w-full h-48 object-cover rounded-lg mb-4">
                    <h3 class="text-xl font-bold text-gray-800">Donat Gula Salju</h3>
                    <p class="text-gray-600 my-2">Klasik tapi ngangenin!</p>
                    <p class="text-2xl font-bold text-green-600">Rp5.000</p>
                </div>

                <!-- Card 2: Donat Topping Coklat -->
                <div class="card bg-white rounded-2xl shadow-md overflow-hidden p-6 text-center">
                    <img src="download (1).jfif" alt="Donat bolong dengan topping coklat dan meses" class="w-full h-48 object-cover rounded-lg mb-4">
                    <h3 class="text-xl font-bold text-gray-800">Donat Coklat Ceria</h3>
                    <p class="text-gray-600 my-2">Lelehan coklatnya bikin hepi!</p>
                    <p class="text-2xl font-bold text-green-600">Rp5.000</p>
                </div>

                <!-- Card 3: Donat Isi Strawberry -->
                <div class="card bg-white rounded-2xl shadow-md overflow-hidden p-6 text-center">
                    <img src="https://placehold.co/400x300/FADADD/D92A5A?text=Donat+Stroberi" alt="Donat isi dengan selai strawberry yang meluber" class="w-full h-48 object-cover rounded-lg mb-4">
                    <h3 class="text-xl font-bold text-gray-800">Donat Bom Stroberi</h3>
                    <p class="text-gray-600 my-2">Kejutan selai di setiap gigitan!</p>
                    <p class="text-2xl font-bold text-green-600">Rp5.000</p>
                </div>

            </div>
        </section>

        <!-- How to Order Section -->
        <section id="pesan" role="region" aria-labelledby="pesan-title" class="mt-16 text-center">
             <h2 id="pesan-title" class="text-3xl font-bold text-center mb-8 text-gray-800">Gimana Cara Ordernya?</h2>
            <div class="bg-white p-8 rounded-2xl shadow-lg">
                <p class="text-lg mb-6 text-gray-700">Kamu bisa beli langsung di sekolah atau pesan online biar nggak kehabisan!</p>
                <div class="flex flex-col md:flex-row justify-center items-center gap-4">
                     <!-- Beli Langsung -->
                    <div class="text-center p-4 rounded-lg bg-gray-100">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 mx-auto text-orange-500 mb-2" viewBox="0 0 20 20" fill="currentColor" role="img" aria-label="Ikon Lokasi"><title>Ikon Lokasi</title><path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd" /></svg>
                        <h3 class="font-bold">Beli Langsung</h3>
                        <p>📍 SMAN 1 Dramaga</p>
                    </div>
                     <!-- WhatsApp -->
                    <a href="https://wa.me/6285773688582?text=Hai,%20aku%20mau%20pesan%20donat%20Kentato!" target="_blank" class="btn bg-green-500 text-white font-bold py-3 px-6 rounded-full flex items-center gap-2 w-full md:w-auto justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-message-circle" role="img" aria-label="Ikon WhatsApp"><title>Ikon WhatsApp</title><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"></path></svg>
                        Chat WhatsApp
                    </a>
                    <!-- DANA -->
                    <div class="text-center p-4 rounded-lg bg-blue-100">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 mx-auto text-blue-500 mb-2" viewBox="0 0 20 20" fill="currentColor" role="img" aria-label="Ikon Dompet Digital"><title>Ikon Dompet Digital</title><path d="M4 4a2 2 0 00-2 2v1h16V6a2 2 0 00-2-2H4z" /><path fill-rule="evenodd" d="M18 9H2v5a2 2 0 002 2h12a2 2 0 002-2V9zM4 13a1 1 0 011-1h1a1 1 0 110 2H5a1 1 0 01-1-1zm3 0a1 1 0 011-1h1a1 1 0 110 2H8a1 1 0 01-1-1z" clip-rule="evenodd" /></svg>
                        <h3 class="font-bold">Bayar via DANA</h3>
                        <p>081283737028</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Order Form Section -->
        <section id="form-pemesanan" role="region" aria-labelledby="form-title" class="mt-16">
            <h2 id="form-title" class="text-3xl font-bold text-center mb-4 text-gray-800">Atau Isi Form di Bawah Ini!</h2>
            <div class="bg-white p-8 rounded-2xl shadow-lg">
                <form id="orderForm">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <!-- Nama Pemesan -->
                        <div>
                            <label for="nama" class="block text-sm font-medium text-gray-700">Nama Kamu</label>
                            <input type="text" id="nama" name="nama" required aria-required="true" class="mt-1 block w-full px-3 py-2 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-orange-500 focus:border-orange-500">
                        </div>
                        <!-- Kelas -->
                        <div>
                            <label for="kelas" class="block text-sm font-medium text-gray-700">Kelas</label>
                            <input type="text" id="kelas" name="kelas" required aria-required="true" class="mt-1 block w-full px-3 py-2 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-orange-500 focus:border-orange-500">
                        </div>
                        <!-- Pilihan Donat -->
                        <div class="md:col-span-2">
                            <label for="varian-donat" class="block text-sm font-medium text-gray-700">Varian Donat</label>
                            <select id="varian-donat" name="varian-donat" required aria-required="true" class="mt-1 block w-full px-3 py-2 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-orange-500 focus:border-orange-500">
                                <option value="">-- Pilih Varian --</option>
                                <option value="Gula Halus - Rp5000">Donat Gula Salju - Rp5.000</option>
                                <option value="Coklat - Rp5000">Donat Coklat Ceria - Rp5.000</option>
                                <option value="Strawberry - Rp5000">Donat Bom Stroberi - Rp5.000</option>
                            </select>
                        </div>
                        <!-- Jumlah -->
                         <div>
                            <label for="jumlah" class="block text-sm font-medium text-gray-700">Jumlah</label>
                            <input type="number" id="jumlah" name="jumlah" min="1" value="1" required aria-required="true" class="mt-1 block w-full px-3 py-2 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-orange-500 focus:border-orange-500">
                        </div>
                    </div>
                    <div class="mt-6">
                        <button type="submit" class="btn w-full bg-orange-500 hover:bg-orange-600 text-white font-bold py-3 px-6 rounded-full">
                            Kirim Pesanan
                        </button>
                    </div>
                </form>
            </div>
        </section>

        <!-- FOMO Section -->
        <section class="mt-16 text-center" aria-live="polite">
             <div class="bg-red-100 border-l-4 border-red-500 text-red-700 p-6 rounded-r-lg shadow-lg" role="alert">
                <p class="font-bold text-lg">Jangan Sampai Kehabisan!</p>
                <p>Anak-anak lain udah pada ngantri, lho. Stok terbatas setiap harinya! Kalau nggak coba, dijamin FOMO!</p>
            </div>
            <p class="mt-6 text-2xl font-extrabold text-gray-800">
                Yuk, buruan pesen Kentato sekarang!
            </p>
        </section>

    </div>

    <!-- Modal Success Message -->
    <div id="successModal" class="modal fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center p-4 opacity-0 pointer-events-none" role="alertdialog" aria-modal="true" aria-labelledby="modal-title" aria-describedby="modal-description">
        <div class="bg-white rounded-2xl shadow-xl p-8 text-center max-w-sm mx-auto">
            <div class="mx-auto flex items-center justify-center h-12 w-12 rounded-full bg-green-100 mb-4">
                <svg class="h-6 w-6 text-green-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Ikon Centang"><title>Ikon Centang</title><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
            </div>
            <h3 id="modal-title" class="text-lg leading-6 font-medium text-gray-900">Pesanan Terkirim!</h3>
            <div id="modal-description" class="mt-2">
                <p class="text-sm text-gray-500">
                    Makasih ya udah pesan! Pesananmu lagi kami siapin. Jangan lupa bayar via DANA ya!
                </p>
            </div>
            <div class="mt-4">
                <button type="button" id="closeModal" class="btn w-full inline-flex justify-center rounded-md border border-transparent shadow-sm px-4 py-2 bg-orange-500 text-base font-medium text-white hover:bg-orange-600 focus:outline-none">
                    Siaaap!
                </button>
            </div>
        </div>
    </div>

    <script>
        // JavaScript for form submission and modal
        const orderForm = document.getElementById('orderForm');
        const successModal = document.getElementById('successModal');
        const closeModal = document.getElementById('closeModal');
        const firstFocusableElement = closeModal; // The close button is the first and only focusable element in the modal
        const lastFocusableElement = closeModal;

        orderForm.addEventListener('submit', function(event) {
            event.preventDefault(); // Prevent actual form submission
            
            // Get form data (optional, for console logging)
            const formData = new FormData(orderForm);
            const orderData = Object.fromEntries(formData.entries());
            console.log('Pesanan Baru:', orderData);
            
            // Show the modal
            successModal.classList.remove('opacity-0', 'pointer-events-none');
            // Focus on the close button when modal opens
            closeModal.focus();
        });

        function hideModal() {
            successModal.classList.add('opacity-0', 'pointer-events-none');
            orderForm.reset(); // Reset the form fields
        }

        closeModal.addEventListener('click', hideModal);
        
        // Close modal if clicking outside of it
        successModal.addEventListener('click', function(event) {
            if (event.target === successModal) {
                hideModal();
            }
        });

        // Trap focus inside the modal for accessibility
        document.addEventListener('keydown', function(e) {
            if (successModal.classList.contains('pointer-events-none')) {
                return; // if modal is not open, do nothing
            }

            let isTabPressed = e.key === 'Tab' || e.keyCode === 9;

            if (!isTabPressed) {
                return;
            }

            if (e.shiftKey) { // if shift key pressed for shift + tab combination
                if (document.activeElement === firstFocusableElement) {
                    lastFocusableElement.focus(); // move focus to the last focusable element
                    e.preventDefault();
                }
            } else { // if tab key is pressed
                if (document.activeElement === lastFocusableElement) { // if focused has reached to last focusable element then focus first focusable element after pressing tab
                    firstFocusableElement.focus(); // move focus to the first focusable element
                    e.preventDefault();
                }
            }
        });
    </script>
</body>
</html>


