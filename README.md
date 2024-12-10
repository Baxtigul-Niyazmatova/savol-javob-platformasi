Bu project stackoverflow ga o'xshagan savol va javob oldadiga web dastur

repository ni clone qilib olish

```bash
   git clone https://github.com/Baxtigul-Niyazmatova/savol-javob-platformasi.git
   cd stack-overflow-clone
```

```bash
   composer install
   npm install
```


```bash
touch database/database.sqlite

php artisan migrate --seed
```

```bash
npm run build || npm run dev
```

```bash
cp .env.example .env
```

```bash
php artisan key:generate
```

```bash
php artisan config:clear
php artisan cache:clear
php artisan route:clear
php artisan view:clear
```

```bash
php artisan serve
```

Admin
email => admin@example.com,
password =>password,

User
email => john@example.com,
password => password,