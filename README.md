# Изменения
Нарушен принцип Single-responsibility. Класс Purchase подразумевает именно покупку, поэтому методы addPurchase() и sum() перенесены в класс Busket.