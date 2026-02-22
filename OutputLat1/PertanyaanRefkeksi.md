1. Apa perbedaan antara @Controller dan @RestController? Dalam kasus apa kamu pakai masing-masing?
   Perbedaan: @Controller itu dipake kalau kita mau nampilin halaman (HTML/Thymeleaf). Jadi dia bakal nyari file di folder templates. Sedangkan @RestController itu isinya @Controller + @ResponseBody, jadi dia langsung balikin data (biasanya JSON atau teks) tanpa nyari file HTML.@Controller: Pas kita mau bikin web yang ada tampilannya (pake Bootstrap, CSS, dll).

@RestController: Pas kita mau bikin API buat aplikasi mobile atau kalau kita mau kirim data mentah aja.