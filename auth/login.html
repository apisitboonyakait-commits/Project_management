<!DOCTYPE html>
<html lang="th">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <link rel="stylesheet" href="style_login.css">
    <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
    <title>เข้าสู่ระบบ PROJECT MANAGEMENT</title>
    <style>
        .password-container {
            position: relative;
            width: 100%;
            margin: 8px 0;
        }

        .password-container input {
            width: 100%;
            padding-right: 40px;
            margin: 0;
        }

        .password-container i {
            position: absolute;
            right: 15px;
            top: 50%;
            transform: translateY(-50%);
            color: #666;
            cursor: pointer;
            transition: color 0.2s;
        }

        .password-container i:hover {
            color: #0d6efd;
        }

        /* 🔥 CSS สำหรับ โลโก้บริษัท 🔥 */
        .company-logo {
            width: 90px;
            height: 90px; 
            object-fit: contain;
            margin-bottom: 15px;
            display: block;
            margin-left: auto;
            margin-right: auto;
            border-radius: 12px;
        }

        /* 🔥 Custom SweetAlert2 Style 🔥 */
        .swal2-popup.my-custom-swal {
            border-radius: 24px !important;
            padding: 2em !important;
            box-shadow: 0 20px 40px rgba(0,0,0,0.2) !important;
            font-family: 'Sarabun', sans-serif !important;
        }
        .swal2-title.my-custom-title {
            font-size: 24px !important;
            font-weight: 700 !important;
            color: #333 !important;
        }
        .swal2-confirm.my-custom-btn {
            border-radius: 50px !important;
            padding: 12px 30px !important;
            font-weight: 600 !important;
            font-size: 16px !important;
            box-shadow: 0 8px 20px rgba(13, 110, 253, 0.3) !important;
            transition: all 0.3s ease !important;
        }
        .swal2-confirm.my-custom-btn:hover {
            transform: translateY(-2px) !important;
            box-shadow: 0 10px 25px rgba(13, 110, 253, 0.4) !important;
        }
    </style>
</head>

<body>

    <div style="position: fixed; top: 20px; left: 50%; transform: translateX(-50%); z-index: 9999; display: flex; flex-direction: column; gap: 10px; align-items: center; width: 100%; pointer-events: none;">
        <!-- Error/Success messages would go here -->
    </div>

    <div class="container" id="container">

        <div class="form-container sign-up">
            <form action="#" id="forgotForm">
                <img src="https://www.bigsara.co.th/images/LOGO-Bigsara.png" alt="Company Logo" class="company-logo">
                
                <h1 style="color: #333; margin-bottom: 10px;">กู้คืนรหัสผ่าน</h1>
                <p style="text-align: center; color: #666; font-size: 13px;">กรุณากรอกอีเมลที่ลงทะเบียนไว้ในระบบ
                    <br>เพื่อรับลิงก์ตั้งรหัสผ่านใหม่</p>
                <input type="email" name="email" placeholder="อีเมลของคุณ (Email)">
                <button type="submit" name="forgot_password"
                    style="margin-top: 20px; width: 100%;">ส่งลิงก์ยืนยัน</button>
            </form>
        </div>

        <div class="form-container sign-in">
            <form action="#" id="loginForm">
                <img src="https://www.bigsara.co.th/images/LOGO-Bigsara.png" alt="Company Logo" class="company-logo">
                
                <h1>PROJECT MANAGEMENT</h1> <span style="margin-bottom: 15px;">BIGSARA COMPANY</span>
                <input type="text" name="username" placeholder="ชื่อผู้ใช้ (Username)">
                
                <div class="password-container">
                    <input type="password" name="password" id="loginPassword" placeholder="รหัสผ่าน (Password)">
                    <i class="fa-solid fa-eye" id="togglePasswordBtn" onclick="togglePassword()"></i>
                </div>

                <button type="submit" name="login" style="margin-top: 20px;">เข้าสู่ระบบ</button>
            </form>
        </div>

        <div class="toggle-container">
            <div class="toggle">
                <div class="toggle-panel toggle-left">
                    <h1>จำรหัสได้แล้ว?</h1>
                    <p>จำรหัสผ่านได้แล้ว? กลับไปหน้าเข้าสู่ระบบ</p>
                    <button class="hidden" id="loginBtn">กลับไปหน้า Login</button>
                </div>
                <div class="toggle-panel toggle-right">
                    <h1>เอ๊ะ! คุณลืมรหัสผ่านงั้นเหรอ?</h1>
                    <p>ลืมรหัสผ่านใช่ไหม? คลิกด้านล่างเพื่อกู้คืน</p>
                    <button class="hidden" id="forgotBtn">ลืมรหัสผ่าน?</button>
                </div>
            </div>
        </div>
    </div>

    <script>
        const container = document.getElementById('container');
        const forgotBtn = document.getElementById('forgotBtn'); 
        const loginBtn = document.getElementById('loginBtn');   

        // 🔥 สำหรับเปิดหน้าลืมรหัสผ่าน

        forgotBtn.addEventListener('click', () => {
            container.classList.add("active");
        });

        loginBtn.addEventListener('click', () => {
            container.classList.remove("active");
        });

        function togglePassword() {
            const passwordInput = document.getElementById('loginPassword');
            const icon = document.getElementById('togglePasswordBtn');

            if (passwordInput.type === 'password') {
                passwordInput.type = 'text';
                icon.classList.remove('fa-eye');
                icon.classList.add('fa-eye-slash');
            } else {
                passwordInput.type = 'password';
                icon.classList.remove('fa-eye-slash');
                icon.classList.add('fa-eye');
            }
        }

        // ตั้งค่าเริ่มต้นให้ SweetAlert2 สวยงามและไม่ทำให้หน้าเว็บขยับ
        const Toast = Swal.mixin({
            scrollbarPadding: false, // ป้องกันหน้าเว็บเลื่อนแนวนอน
            heightAuto: false, // 🔥 ป้องกันหน้าเว็บขยับขึ้น (ไม่ให้ swal ไปกวน height: 100vh ของ body)
            customClass: {
                popup: 'my-custom-swal',
                title: 'my-custom-title',
                confirmButton: 'my-custom-btn'
            },
            showClass: {
                popup: 'animate__animated animate__zoomIn animate__faster'
            },
            hideClass: {
                popup: 'animate__animated animate__zoomOut animate__faster'
            }
        });

        // 🔥 SweetAlert2 สำหรับแจ้งเตือนฟอร์ม 🔥
        document.getElementById('loginForm').addEventListener('submit', function(e) {
            e.preventDefault(); // หยุดการเปลี่ยนหน้า
            const username = this.querySelector('input[name="username"]').value;
            const password = this.querySelector('input[name="password"]').value;

            if (!username || !password) {
                Toast.fire({
                    icon: 'warning',
                    title: 'ข้อมูลไม่ครบถ้วน',
                    text: 'กรุณากรอกชื่อผู้ใช้และรหัสผ่าน',
                    confirmButtonColor: '#0d6efd',
                    confirmButtonText: 'ตกลง'
                });
            } else {
                Toast.fire({
                    icon: 'success',
                    title: 'เข้าสู่ระบบสำเร็จ!',
                    text: 'ยินดีต้อนรับกลับมา',
                    confirmButtonColor: '#0d6efd',
                    confirmButtonText: 'ดำเนินการต่อ',
                    timer: 2000,
                    timerProgressBar: true
                });
            }
        });

        document.getElementById('forgotForm').addEventListener('submit', function(e) {
            e.preventDefault(); // หยุดการเปลี่ยนหน้า
            const email = this.querySelector('input[name="email"]').value;

            if (!email) {
                Toast.fire({
                    icon: 'warning',
                    title: 'ข้อมูลไม่ครบถ้วน',
                    text: 'กรุณากรอกอีเมลที่ลงทะเบียนไว้',
                    confirmButtonColor: '#0d6efd',
                    confirmButtonText: 'ตกลง'
                });
            } else {
                Toast.fire({
                    icon: 'success',
                    title: 'ส่งลิงก์สำเร็จ',
                    text: 'ระบบได้ส่งลิงก์ตั้งรหัสผ่านใหม่ไปยังอีเมลของคุณแล้ว',
                    confirmButtonColor: '#0d6efd',
                    confirmButtonText: 'ตกลง'
                }).then(() => {
                    this.reset(); // ล้างข้อมูลในฟอร์ม
                    container.classList.remove("active"); // กลับไปหน้าเข้าสู่ระบบ
                });
            }
        });
    </script>
</body>
</html>