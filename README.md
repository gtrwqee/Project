# Project

mkdir my-website
cd my-website
git init

# Создаём базовый index.html
cat > index.html << 'EOF'
<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8">
    <title>Моя страница</title>
  </head>
  <body>
    <!-- Сюда позже подключим header -->
    <main>
      <h1>Привет, мир!</h1>
      <p>Это базовая страница.</p>
    </main>
  </body>
</html>
EOF

git add index.html
git commit -m "init: базовый index.html"
