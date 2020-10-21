# Датасет по банковским вкладам в г. Москва #

## Описание ##
В рамках данного датасета проведена агрегация данных по условиям вкладов разных банков в г. Москва. 
Данная информация может быть использована как потенциальными клиентами для выбора наиболее подходящего вклада в зависимости от их потребностей, так и финансовыми учреждениями для сравнения своих предложений по вкладам относительно предложений своих конкурентов.

С учетом того, что во многих вкладах доходность зависит от размещенной на вкладе суммы, все возможные варианты доходности по одному вкладу перечислены в датасете в виде отдельных строк с указанием ставки и диапазона суммы, в рамках которой применяется ставка.

## Источники ##
1. https://www.banki.ru/products/deposits/

## Структура ##
- Банк
- Финансовый рейтинг надежности банка	(по общим активам)
- Название вклада
- Срок действия предложения	
- Ставка, % годовых
- Минимальный срок вклада, дни
- Максимальный срок вклада, дни	
- Минимальная сумма вклада, руб. (для указанной в строке ставки)
- Максимальная сумма вклада, руб.	(для указанной в строке ставки)
- Возможность пополнения (да/нет/условия)	
- Возможность расторжения	(да/нет/условия)	
- Частичное снятие (да/нет/условия)	
- Капитализация	(способ капитализации)	
- Дополнительные условия (в виде списка)
