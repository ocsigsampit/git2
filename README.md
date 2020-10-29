"# git2" 

Untuk mem-push perubahan pada branch baru ke remote dengan membentuk branch baru tsb di remote :

1. Di repo lokal, buat branch baru misal "cabang" dengan perintah : git checkout -b "cabang"
2. Di repo lokal branch cabang ini, terjadi perubahan dan commit
3. Push dengan command : git push -u origin cabang.
4. Maka akan muncul branch baru bernama "cabang" dengan keadaan sesuai commit di branch "cabang" lokal.
