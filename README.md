<div align="center">
  
  ![GitHub repo size](https://img.shields.io/github/repo-size/smzamil1/cryptex)
  
  [![Twitter Follow](https://img.shields.io/twitter/follow/Crypto_Zamil?style=social)](https://twitter.com/intent/follow?screen_name=codewithsadee)
  [![YouTube Video Views](https://img.shields.io/youtube/views/ux3o7jDhvOc?style=social)](https://youtu.be/ux3o7jDhvOc)

  <br />
  <br />

  <h2 align="center">Cryptex - Cryptocurrency Website</h2>

  Cryptex is a fully responsive cryptocurrency website, <br />Responsive for all devices, build using HTML, CSS, and JavaScript.

  <a href="https://codewithsadee.github.io/cryptex/"><strong>➥ Live Demo</strong></a>

</div>

<br />

### Demo Screeshots

![Cryptex Desktop Demo](./readme-images/desktop.png "Desktop Demo")

### Prerequisites

Before you begin, ensure you have met the following requirements:

* [Git](https://git-scm.com/downloads "Download Git") must be installed on your operating system.

### Run Locally

To run **Cryptex** locally, run this command on your git bash:

Linux and macOS:

```bash
sudo git clone https://github.com/codewithsadee/cryptex.git
```

Windows:

```bash
git clone https://github.com/codewithsadee/cryptex.git
```

### Contact

If you want to contact with me you can reach me at [Twitter](https://www.twitter.com/Crypto_Zamil).

### License

This project is **free to use** and does not contains any license.






<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Meta Tag -->
    <title>Secure Checkout - Mega Shop</title>
    <meta name="title" content="Secure Checkout - Mega Shop">
    <link rel="icon" href="https://pay.meghashop.pro/uploads/favicon/652823feb1adc1-60278392-57622838.png">
    <meta name="description" content="">

    
    <!-- Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://pay.meghashop.pro/">
    <meta property="og:title" content="Secure Checkout - Mega Shop">
    <meta property="og:description" content="">
    <meta property="og:image" content="https://pay.meghashop.pro/uploads/fb_og_image/65282419d6e4b7-92916218-30317001.png">

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:url" content="https://pay.meghashop.pro/">
    <meta property="twitter:title" content="Secure Checkout - Mega Shop">
    <meta property="twitter:description" content="">
    <meta property="twitter:image" content="https://pay.meghashop.pro/uploads/twitter_og_image/65282415a75c35-94350881-59097399.png">

    <!-- CSS -->
    <link href="https://pay.meghashop.pro/assets/template/css/uddoktapay.css" rel="stylesheet">
    <!-- Toastr -->
    <link rel="stylesheet" href="https://pay.meghashop.pro/assets/dashboard/plugins/toastr/toastr.min.css">

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">

    <link href="https://fonts.googleapis.com/css2?family=Baloo+Da+2:wght@400;500;600;700;800&family=Inter:wght@100;200;300;400&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">

    <!-- Custom CSS -->
    <style type="text/css">
        * {
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(350deg, #f4f9ff, #edf4ffc9), url('https://pay.meghashop.pro/assets/template/images/body.png');
        }


        .font-bangla {
            font-family: 'Baloo Da 2', cursive;
        }


        
        /* bKash */
        .brand-bg {
            --tw-bg-opacity: 1;
            background-color: rgb(207 39 113 / var(--tw-bg-opacity));
        }

        .brand-hr {
            --tw-border-opacity: 1;
            border-color: rgb(191 24 97 / var(--tw-border-opacity));
        }

        .brand-btn {
            --tw-bg-opacity: 1;
            background-color: rgb(207 39 113 / var(--tw-bg-opacity));
        }

        .brand-btn:hover {
            --tw-bg-opacity: 1;
            background-color: rgb(231 57 133 / var(--tw-bg-opacity));
        }

            </style>
</head>


<body class="w-full min-h-screen sm:h-auto sm:p-12 sm:flex sm:items-center sm:justify-center">
        <!-- Overlay Start-->
    <div id="page-overlay" class="visible incoming">
        <div class="loader-wrapper-outer">
            <div class="loader-wrapper-inner">
                <div class="lds-double-ring">
                    <div></div>
                    <div></div>
                    <div>
                        <div></div>
                    </div>
                    <div>
                        <div></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Overlay End -->
    <!-- Full Design -->
    <div class="up-container max-w-md overflow-hidden mx-auto p-8 sm:relative sm:bg-white sm:rounded-lg sm:shadow-lg sm:shadow-[#0057d0]/10 sm:min-w-[650px] sm:flex sm:flex-wrap">

        <!-- nav -->
        <div class="w-full h-12 shadow-md shadow-[#0057d0]/5 rounded-lg overflow-hidden flex justify-between items-center p-5 bg-white sm:bg-[#fbfcff]  sm:shadow-none sm:ring-1 sm:ring-[#0057d0]/10">
            <div class="">
                <a href="https://pay.meghashop.pro/payment/69074c5c68f34d869bee4b69f1e08e6d12f2dfbe">
                    <svg width="19" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M9.5 1C4.80558 1 1 4.80558 1 9.5C1 14.1944 4.80558 18 9.5 18C14.1944 18 18 14.1944 18 9.5C18 4.80558 14.1944 1 9.5 1Z" stroke="#6D7F9A" stroke-width="1.5"></path>
                        <path d="M10.7749 12.9L7.3749 9.50002L10.7749 6.10002" stroke="#94A9C7" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
                    </svg>
                </a>
            </div>
            <div class="flex items-center">
                <a href="#" class="mr-5" id="language" data-language="bangla">
                    <svg width="17" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M5.39719 7.97288L4.88063 9.5H3.5625L5.77362 3.5625H7.29837L9.5 9.5H8.11419L7.59762 7.97288H5.39719ZM7.33756 7.09888L6.53125 4.69775H6.47306L5.66675 7.09888H7.33875H7.33756Z" fill="#94A9C7"></path>
                        <path d="M0 2.375C0 1.74511 0.250223 1.14102 0.695621 0.695621C1.14102 0.250223 1.74511 0 2.375 0L10.6875 0C11.3174 0 11.9215 0.250223 12.3669 0.695621C12.8123 1.14102 13.0625 1.74511 13.0625 2.375V5.9375H16.625C17.2549 5.9375 17.859 6.18772 18.3044 6.63312C18.7498 7.07852 19 7.68261 19 8.3125V16.625C19 17.2549 18.7498 17.859 18.3044 18.3044C17.859 18.7498 17.2549 19 16.625 19H8.3125C7.68261 19 7.07852 18.7498 6.63312 18.3044C6.18772 17.859 5.9375 17.2549 5.9375 16.625V13.0625H2.375C1.74511 13.0625 1.14102 12.8123 0.695621 12.3669C0.250223 11.9215 0 11.3174 0 10.6875V2.375ZM2.375 1.1875C2.06006 1.1875 1.75801 1.31261 1.53531 1.53531C1.31261 1.75801 1.1875 2.06006 1.1875 2.375V10.6875C1.1875 11.0024 1.31261 11.3045 1.53531 11.5272C1.75801 11.7499 2.06006 11.875 2.375 11.875H10.6875C11.0024 11.875 11.3045 11.7499 11.5272 11.5272C11.7499 11.3045 11.875 11.0024 11.875 10.6875V2.375C11.875 2.06006 11.7499 1.75801 11.5272 1.53531C11.3045 1.31261 11.0024 1.1875 10.6875 1.1875H2.375ZM10.8514 13.0566C11.0806 13.414 11.3287 13.7489 11.5995 14.0612C10.7112 14.744 9.61281 15.2499 8.3125 15.5954C8.52388 15.8531 8.84806 16.3495 8.97156 16.625C10.3075 16.1987 11.4416 15.6227 12.3987 14.8509C13.3214 15.6406 14.4638 16.2343 15.8781 16.5989C16.036 16.2972 16.3697 15.7997 16.625 15.542C15.2891 15.2416 14.1823 14.7179 13.2763 14.0173C14.0849 13.1302 14.7274 12.0567 15.2012 10.7433H16.625V9.5H13.0625V10.7433H13.9709C13.5933 11.7456 13.0922 12.5792 12.4604 13.2727C12.2859 13.0868 12.1214 12.8918 11.9676 12.6884C11.6325 12.9033 11.2485 13.0299 10.8514 13.0566Z" fill="#6D7F9A"></path>
                    </svg>
                </a>
                <form action="https://pay.meghashop.pro/checkout/cancel" method="post" accept-charset="utf-8">
<input type="hidden" name="invoice_id" value="fqu6ALJ22HstNOye5x3i" />
<input type="hidden" name="csrf_rt_77edf3b0ce_token" value="0f7c6fe2ffd11d165867ff8bb9eb5a61" />                                                           
                <button type="submit">
                    <svg width="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M13 1L1 13" stroke="#94A9C7" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
                        <path d="M1 1L13 13" stroke="#6D7F9A" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
                    </svg>
                </button>
                </form>            </div>
        </div>
        <!--END nav -->

        <!-- bKash Transaction -->
        <div class="w-full">
            <div class="flex flex-col sm:flex-row flex-wrap sm:mt-5 sm:justify-between sm:items-center">
                <div class="w-full h-20 mb-4 sm:mt-0 flex justify-center items-center">
                    <img src="https://pay.meghashop.pro/assets/template/images/bkash.png" alt="Logo" class="h-[80%]">
                </div>
                <div class="bg-white shadow shadow-[#0057d0]/5 rounded-lg px-5 py-3 sm:h-[85px] flex items-center sm:w-[70%] sm:shadow-none sm:ring-1 sm:ring-[#0057d0]/10">
                    <div class="w-[55px] h-[55px] p-1.5 flex justify-center items-center mr-4 ring-1 ring-[#0057d0]/10 rounded-full">
                        <img src="https://pay.meghashop.pro/uploads/logo/652823f8b73106-82386715-61141400.png" alt="Mega Shop" class="w-[80%]">
                    </div>
                    <div class="flex flex-col">
                        <h3 class="font-semibold text-[#6D7F9A]">Mega Shop</h3>
                        <span class="text-[#94a9c7] text-sm font-bangla">ইনভয়েস আইডিঃ</span>
                        <p class="text-[#6D7F9A] text-sm select-all">fqu6ALJ22HstNOye5x3i</p>
                    </div>
                </div>
                <div class="bg-white shadow shadow-[#0057d0]/5 rounded-lg py-3 px-2 sm:h-[85px] flex flex-col sm:items-center sm:justify-center sm:shadow-none sm:ring-1 sm:ring-[#0057d0]/10 mt-3 sm:w-[25%] sm:mt-0">
                    <h1 class="text-xl sm:text-2xl font-semibold text-[#6D7F9A]">৳ 100.00</h1>
                                    </div>
            </div>

            <form action="https://pay.meghashop.pro/checkout/verify-payment-data" class="actionForm" method="post" accept-charset="utf-8">
<input type="hidden" name="payment_id" value="69074c5c68f34d869bee4b69f1e08e6d12f2dfbe" />
<input type="hidden" name="payment_method" value="bkash" />
<input type="hidden" name="payment_method_id" value="1" />
                                                                                                     <input type="hidden" name="csrf_rt_77edf3b0ce_token" value="0f7c6fe2ffd11d165867ff8bb9eb5a61" />

                            <!-- Transaction Id -->
                <div class="brand-bg p-5 mt-3 rounded-lg overflow-auto">
                    <div class="text-center mt-3">
                        <h2 class="mb-3 font-semibold text-white font-bangla">ট্রান্সজেকশন আইডি দিন</h2>
                        <input type="text" name="transaction_id" placeholder="ট্রান্সজেকশন আইডি দিন" class="font-bangla appearance-none w-full text-[15px] rounded-[10px] sm:bg-[#fbfcff] shadow shadow-[#0057d0]/5 px-5 py-3.5 placeholder-[#94A9C7] focus:outline-none focus:ring-1 focus:ring-[#0057d0]" maxlength="10" required>
                    </div>

                    <!-- Phone Number -->
                    <div id="sender_number" class="text-center mt-3 hidden">
                        <h2 class="mb-3 font-semibold text-white font-bangla">ফোন নম্বর লিখুন</h2>
                        <input type="text" name="phone_number" placeholder="ফোন নম্বর লিখুন" class="font-bangla appearance-none w-full text-[15px] rounded-[10px] sm:bg-[#fbfcff] shadow shadow-[#0057d0]/5 px-5 py-3.5 placeholder-[#94A9C7] focus:outline-none focus:ring-1 focus:ring-[#0057d0]" maxlength="12">
                    </div>
                    <!-- Phone Number -->

                    <div class="">
                        <ul class="mt-5 text-slate-200">
                            <li class="flex text-sm">
                                <div><span class="inline-block w-1.5 h-1.5 mr-2 bg-white rounded-full mb-0.5"></span>
                                </div>
                                                                    <p class="font-bangla">*247# ডায়াল করে আপনার BKASH মোবাইল মেনুতে যান অথবা BKASH অ্যাপে যান।</p>
                                                            </li>
                            <hr class="brand-hr my-3">
                            <li class="flex text-sm">
                                <div><span class="inline-block w-1.5 h-1.5 mr-2 bg-white rounded-full mb-0.5"></span>
                                </div>
                                <p class="font-bangla">                                    <span class="text-yellow-300 font-semibold ml-1">
                                        "Send Money"
                                    </span> -এ ক্লিক করুন।                                </p>
                            </li>
                            <hr class="brand-hr my-3">
                            <li class="flex text-sm">
                                <div><span class="inline-block w-1.5 h-1.5 mr-2 bg-white rounded-full mb-0.5"></span>
                                </div>
                                <p class="sm:w-[90%] font-bangla">প্রাপক নম্বর হিসেবে এই নম্বরটি লিখুনঃ                                    <span class="text-yellow-300 font-semibold ml-1"> 01746081212</span>
                                    <a href="#" class="px-2 py-0.5 mx-2 rounded-md inline-block bg-[#00000040] copy" data-clipboard-text="01746081212"><img src="https://pay.meghashop.pro/assets/template/images/icon/copy.png" class="w-3 inline mr-2" alt="Copy">Copy</a>
                                                                    </p>
                            </li>

                            
                            <hr class="brand-hr my-3">
                            <li class="flex text-sm">
                                <div><span class="inline-block w-1.5 h-1.5 mr-2 bg-white rounded-full mb-0.5"></span>
                                </div>
                                <p class="font-bangla">টাকার পরিমাণঃ <span class="text-yellow-300 font-semibold ml-1"> 100.00</span></p>
                            </li>
                            <hr class="brand-hr my-3">
                            <li class="flex text-sm">
                                <div><span class="inline-block w-1.5 h-1.5 mr-2 bg-white rounded-full mb-0.5"></span>
                                </div>
                                <p class="font-bangla">নিশ্চিত করতে এখন আপনার BKASH মোবাইল মেনু পিন লিখুন।</p>
                            </li>
                            <hr class="brand-hr my-3">
                            <li class="flex text-sm">
                                <div><span class="inline-block w-1.5 h-1.5 mr-2 bg-white rounded-full mb-0.5"></span>
                                </div>
                                <p class="font-bangla">সবকিছু ঠিক থাকলে, আপনি BKASH থেকে একটি নিশ্চিতকরণ বার্তা পাবেন।</p>
                            </li>
                            <hr class="brand-hr my-3">
                            <li class="flex text-sm">
                                <div><span class="inline-block w-1.5 h-1.5 mr-2 bg-white rounded-full mb-0.5"></span>
                                </div>
                                <p class="font-bangla">এখন উপরের বক্সে আপনার<span class="text-yellow-300 font-semibold ml-1">Transaction ID</span> দিন এবং নিচের<span class="text-yellow-300 font-semibold ml-1">VERIFY</span> বাটনে ক্লিক করুন।</p>
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- END Transaction Id -->
            



            <div class="mt-5">
                <button type="submit" id="form_submit" class="brand-btn block rounded-[10px] px-4 py-3.5 text-center font-semibold text-white transition-colors w-full">VERIFY</button>
            </div>
            </form>        </div>
        <!--END bKash Transaction -->
    </div>
    <!-- END Full Design -->

    <!-- jQuery -->
    <script src="https://pay.meghashop.pro/assets/dashboard/plugins/jquery/jquery.min.js"></script>
    <!-- Redirect -->
    <script src="https://pay.meghashop.pro/assets/template/js/jquery.redirect.js"></script>
    <!-- Toastr -->
    <script src="https://pay.meghashop.pro/assets/dashboard/plugins/toastr/toastr.min.js"></script>
    <!-- Clipboard -->
    <script src="https://pay.meghashop.pro/assets/dashboard/plugins/clipboard-js/clipboard.min.js"></script>
    <!-- Custom -->
    <script>
        var site_url = 'https://pay.meghashop.pro/';

        $(document).ready(function() {
            // Clipboard
            var clipboard = new ClipboardJS('.copy');
            clipboard.on('success', function(e) {
                toastr.success('Copied!')
            });

            // Maax Length
            var minLength = 8;
            var maxLength = 10;
            $(document).on('keydown keyup change', '#maxLength', function() {
                var char = $(this).val();
                var charLength = $(this).val().length;
                if (charLength >= maxLength) {
                    $(this).val(char.substring(0, maxLength));
                }
            });

            // Change Language
            $(document).on('click', '#language', function() {
                var _action = site_url + 'change-language';
                var _language = $(this).attr('data-language');
                $.ajax({
                    url: _action,
                    data: {
                        'csrf_rt_77edf3b0ce_token': '0f7c6fe2ffd11d165867ff8bb9eb5a61',
                        language: _language
                    },
                    method: 'POST',
                    dataType: 'JSON'
                }).done(function(response) {
                    window.location.reload(true);
                });
            });

            // Action Form
            $(document).on('submit', '.actionForm', function(e) {
                e.preventDefault();
                var spinner = $('#page-overlay');
                spinner.show();
                var button = $('#form_submit');
                var isDisabled = true;
                button.attr('disabled', isDisabled);
                var _that = $(this),
                    _action = _that.attr("action");
                $.ajax({
                    url: _action,
                    data: $(this).serialize(),
                    method: 'POST',
                    dataType: 'JSON'
                }).done(function(response) {
                    spinner.hide();
                    if (response.status === 'success') {
                        toastr.success(response.message);
                        if (response.type === 'apiv2' && response.return_type === 'post') {
                            setTimeout(function() {
                                $.redirect(response.return_url, {
                                    invoice_id: response.invoice_id
                                });
                            }, 500);
                        } else if (response.type === 'invoice' || response.type === 'link' || response.type === 'resellercamp') {
                            setTimeout(function() {
                                $.redirect(response.return_url, {
                                    invoice_id: response.invoice_id
                                });
                            }, 500);
                        } else {
                            setTimeout(function() {
                                window.location = response.return_url;
                            }, 500);
                        }
                    } else if (response.status === 'pending') {
                        toastr.warning(response.message);
                                                    setTimeout(function() {
                                $.redirect(site_url + 'checkout/pending', {
                                    invoice_id: response.invoice_id
                                });
                            }, 1500);
                                            } else {
                        if (response.errorCode === 'input_number') {
                            button.attr('disabled', !isDisabled);
                            toastr.warning(response.message);
                            $('#sender_number').show();
                        } else {
                            button.attr('disabled', !isDisabled);
                            toastr.error(response.message);
                        }
                    }
                });
            });

                            // QR Code
                var modal = document.getElementById("contentQR");
                var btn = document.getElementById("showQR");
                var span = document.getElementsByClassName("close")[0];
                btn.onclick = function() {
                    modal.style.display = "flex";
                }

                span.onclick = function() {
                    modal.style.display = "none";
                }

                window.onclick = function(event) {
                    if (event.target == modal) {
                        modal.style.display = "none";
                    }
                }
                    });
    </script>

    </body>

</html>