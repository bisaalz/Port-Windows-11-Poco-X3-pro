## Перехід від старого керівництва до нового, або видалення Windows
> За допомогою даного керівництва, ви можете відновити стандартну таблицю розділів, для того щоби видалити Windows, або щоби перейти до нової інструкції по встановленню Windows

> Вам не потрібно робити цей крок, якщо ви не дотримувалися старого керівництва
> 
# Відновлення стандартної таблиці розділів

Замініть <gpt_both0.bin> на шлях до файлу gpt_both0.bin. ви можете знайти його на [сторінці релізів](../../../../releases/tag/binaries)

```cmd
fastboot flash partition:0 <gpt_both0.bin>
````

# Очищення userdata, щоб уникнути нескінченного завантаження і відновити розмір файлової системи
```cmd
fastboot -w
````

## [Наступний крок: Розмітка](/guide/Ukrainian/1-partition-uk.md)
