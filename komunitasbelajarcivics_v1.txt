window.addEventListener("load", function() {console.log("Halaman dan semua gambar sudah dimuat.");  var img = document.getElementById("homepage-img");if (img) {if (img.getAttribute("data-src")) {img.src = img.getAttribute("data-src");}img.classList.add("loaded");}
var banner = document.getElementById("banner"); if (banner) {banner.style.opacity = "1";}});
