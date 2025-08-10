# CloudShare - File Hosting dengan Vercel

## Cara Deploy

1. **Fork repository ini**
2. **Setup GitHub Token:**
   - Buka GitHub → Settings → Developer settings → Personal access tokens
   - Buat token baru dengan scope `repo`
   - Copy token
3. **Update konfigurasi:**
   - Edit `script.js` bagian `CONFIG`:
     - `githubRepo`: `username/nama-repo-anda`
     - `githubToken`: `token-github-anda`
     - `adminPassword`: `password-admin-anda`
4. **Deploy ke Vercel:**
   - Login ke [vercel.com](https://vercel.com)
   - Import dari GitHub
   - Pilih repository ini
   - Deploy

## Fitur

- ✅ Upload file via drag & drop
- ✅ Download dengan kontrol admin
- ✅ Disable/enable download global
- ✅ Delete file (admin only)
- ✅ UI modern dengan ikon
- ✅ Responsive design
- ✅ Progress upload
- ✅ File type icons

## Struktur Folder

