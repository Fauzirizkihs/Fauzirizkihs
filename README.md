
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Penjualan Tiket</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="login-form" id="login-form">
            <h2>Login</h2>
            <form id="loginForm">
                <label for="username">User Name:</label>
                <input type="text" id="username" name="username" required>
                <label for="phone">No Handphone:</label>
                <input type="text" id="phone" name="phone" required>
                <label for="email">Email:</label> 
                <input type="email" id="email" name="email" required>
                <label for="ktp">Poto KTP:</label>
                <input type="file" id="ktp" name="ktp" required>
                <button type="submit">Login</button>
            </form>
        </div>
        
        <div class="ticket-form" id="ticket-form" style="display:none;">
            <h1>Pemesanan Tiket</h1>
            <form id="ticketForm">
                <label for="match">Pilih Jadwal Pertandingan:</label>
                <select id="match" name="match" required>
                    <option value="match1">Persib vs Persebaya (08/08/24)</option>
                    <option value="match2">Persib vs Persija (18/08/24)</option>
                    <option value="match3">Bali United vs Persib (27/08/24)</option>
                    <option value="match4">PSM Makassar vs Persib (05/09/24)</option>
                    <option value="match5">Persib vs RANS FC (20/09/24)</option>
                    <option value="match6">Madura vs Persib (02/10/24)</option>
                    <option value="match7">Persib vs Borneo FC (17/10/24)</option>
                    <option value="match8">PSS Sleman vs Persib (23/10/24)</option>
                    <option value="match9">Persib vs Persita (03/11/24)</option>
                </select>
                
                <label for="tribun">Pilih Tribun:</label>
                <select id="tribun" name="tribun" required>
                    <option value="BARAT VIP">BARAT VIP</option>
                    <option value="Timur">Timur</option>
                    <option value="Utara">Utara</option>
                    <option value="Selatan">Selatan</option>
                </select>
                <label for="jumlah">Jumlah Tiket:</label>
                <input type="number" id="jumlah" name="jumlah" min="1" required>
                <label for="harga">Harga Tiket:</label>
                <input type="text" id="harga" name="harga" readonly>
                <button type="submit">Beli Tiket</button>
            </form>
        </div>
    </div>
    <script src="javascript.js"></script>
</body>
</html>

