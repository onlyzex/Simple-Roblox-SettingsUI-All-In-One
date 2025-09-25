# 🎭 Simple Settings UI System All In One for Roblox
This repository presents a complete Settings UI and Working Function system, built using the Lua scripting language for the Roblox platform. The script delivers a modern, responsive, and dynamic user interface (UI), enabling players to express themselves with a variety of custom emotes and animations in-game.

# ✨ Key Features
Dynamic & Adaptive UI: The entire interface is created directly through the script, ensuring flexibility and easy integration into any game. Its responsive design, powered by UIScale, will adapt to any screen size, from mobile devices to PC, for a consistently clean look.

Seamless User Experience: Enjoy smooth UI transitions with elegant fade-in and fade-out effects, all powered by TweenService.
Full-Fledged Functionality:
Automatic Scale Custom Setting List: Settings Function buttons are dynamically created based on your provided data.
Toggle Control: A convenient "Gear Settings Icon" button allows players to open and close at any time.

# 🚀 How to Use
1. Place `SettingsUIByIbraa` inside `StarterGui` in Roblox Studio.
3. Customize the setting data table within the script with your own function and names.
3. This code provides the perfect foundation for building a professional-looking and fully functional emote system for your game.

Developed by Ibra

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 🎭 Simple Setting UI Script Roblox

Repositori ini menghadirkan sistem Setting yang lengkap, dibuat menggunakan bahasa skrip Lua untuk platform Roblox. Skrip ini menyediakan antarmuka pengguna (UI) yang modern, responsif, dan dinamis, memungkinkan pemain untuk mengekspresikan diri dengan beragam fungsi setting dan fungsi grafis kustom di dalam game.

### ✨ Fitur Utama

* **UI Dinamis & Adaptif**: Seluruh antarmuka dibuat langsung melalui skrip, memastikan fleksibilitas dan kemudahan integrasi ke dalam game mana pun. Desain responsifnya, yang didukung oleh **`UIScale`**, akan menyesuaikan dengan ukuran layar apa pun—dari perangkat seluler hingga PC—untuk tampilan yang selalu rapi.

* **Pengalaman Pengguna Tanpa Hambatan**: Nikmati transisi UI yang halus dengan efek `fade-in` dan `fade-out` yang elegan, semuanya didukung oleh **`TweenService`**.

* **Fungsionalitas Penuh**:
    * **Daftar Function Otomatis**: Tombol-tombol setting dibuat secara dinamis berdasarkan data yang Anda sediakan.
    * **Custom Settings**: Kalian bisa custom fungsi yang ingin kalian tambahkan dengan mudah.
    * **Kontrol Setting**: Tombol "Buka dan Tutup Settings UI" yang praktis memungkinkan pemain untuk mengakses setting in game kapan saja.

### 🚀 Cara Penggunaan

1.  Tempatkan **`SettingsUIByIbraa` ** ini di dalam `StarterGui` di Roblox Studio.
2.  Sesuaikan tabel data **`setting`** di dalam skrip dengan **`function setting`** dan nama milik Anda sendiri.
3.  Kode ini menyediakan fondasi sempurna untuk membangun sistem Setting Function yang terlihat profesional dan berfungsi penuh untuk game Anda.

-----------------------------------------------------

# Custom Your Function Dance:
find this and change it by yourself
```lua
-- ========== Isi Settings ========== (Bisa Custom Sendiri, tinggal copy function dan sesuaikan)
createToggle(contentFrame, "No Shadows", false, function(on)
	Lighting.GlobalShadows = not on
end)

```
Developed by Ibra :D
