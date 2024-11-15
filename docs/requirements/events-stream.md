## Содержание

1. [Диаграмма классов](#диаграмма-классов)
2. [Диаграмма вариантов использования и глоссарий](#диаграмма-вариантов-использования-и-глоссарий)
3. [Диаграммы активности](#диаграммы-активности)
4. [Диаграммы последовательности](#диаграммы-последовательности)
5. [Диаграммы состояний](#диаграммы-состояний)
6. [Диаграммы компонентов и развёртывания](#диаграммы-компонентов-и-развёртывания)

---

## Диаграмма классов

Диаграмма классов показывает основные сущности системы, их атрибуты и методы, а также связи между ними. Эта диаграмма служит основой для понимания структуры системы и её ключевых компонентов. В ней представлены различные классы, которые взаимодействуют друг с другом, обеспечивая выполнение всех необходимых функций приложения. [Ссылка на диаграмму классов](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/Class%20Diagram.png).

Глоссарий описывает все используемые в диаграмме классов термины. В глоссарии содержится информация о каждом из классов, его атрибутах и методах, а также об их предназначении и взаимосвязях. Это помогает лучше понять, как функционирует система и какие термины используются для описания конкретных элементов. [Ссылка на глоссарий диаграммы классов](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/glossary-class-diagram.md).

## Диаграмма вариантов использования и глоссарий

Диаграмма вариантов использования описывает функциональные возможности приложения. Она представляет собой наглядное отображение всех возможных сценариев взаимодействия пользователей с системой. Варианты использования показывают, какие действия может совершать пользователь и как система реагирует на эти действия. [Ссылка на диаграмму вариантов использования](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/Use%20Case.png).

Глоссарий описывает все используемые термины. В нём даётся детальное объяснение каждого из вариантов использования и всех терминов, встречающихся в диаграмме. Это помогает более глубоко понять все процессы, происходящие в системе, а также создать единый подход к описанию функционала. [Ссылка на глоссарий диаграммы вариантов использования](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/glossary-use-case.md).

## Диаграммы активности

Диаграммы активности показывают последовательность действий в рамках определённых процессов приложения.

- [Прохождение урока](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/active/Passing%20Lesson.png) - Диаграмма, описывающая процесс выбора продукта пользователем. Она показывает, как пользователь просматривает каталог товаров, применяет фильтры и выбирает нужный товар для покупки.
- [Прохождение теста](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/active/Passing%20Quiz.png) - Диаграмма, описывающая процесс покупки продукта. Включает в себя шаги от добавления товара в корзину до подтверждения заказа и оформления покупки.
- [Прохождение задания](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/active/Passing%20Task.png) - Диаграмма, отображающая процесс оплаты выбранного продукта. Показывает, какие действия выполняет пользователь для оплаты, включая ввод данных платёжной карты и подтверждение платежа.

## Диаграммы последовательности

Диаграммы последовательности описывают взаимодействие между объектами системы в рамках различных процессов.

- [Регистрация](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/sequence/Sign%20Up.png) - Диаграмма последовательности, описывающая процесс регистрации нового пользователя в системе. Показывает шаги, которые пользователь проходит для создания учётной записи, и взаимодействие с системой для успешной регистрации.
- [Прохождение и выбор теста](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/sequence/Compiler.png) - Диаграмма, отображающая процесс выбора продукта. Показывает, как пользователь взаимодействует с системой при поиске и выборе товаров.
- [Заход в приложение](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/sequence/First%20Start.png) - Диаграмма, описывающая процесс покупки товара, включая добавление в корзину, подтверждение заказа и взаимодействие с системой для завершения покупки.

## Диаграммы состояний

Диаграммы состояний разработаны на основе мокапов и показывают изменения состояния приложения при взаимодействии пользователя.

- [Регистрация](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/state/Sign%20Up%20In.png) - Диаграмма состояния, описывающая все возможные состояния процесса регистрации пользователя, начиная с открытия формы регистрации и заканчивая успешным созданием аккаунта.
- [Выбор урока](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/state/Select%20Lesson.png) - Диаграмма, показывающая различные состояния при выборе урока.

## Диаграммы компонентов и развёртывания

Диаграммы компонентов и развёртывания демонстрируют структуру приложения и его инфраструктуру. Эти диаграммы показывают, как различные компоненты приложения взаимодействуют друг с другом, а также как система развёрнута на серверах или облачной платформе. Диаграмма компонентов описывает основные модули приложения и их взаимодействие, а диаграмма развёртывания показывает, как эти компоненты размещены и соединены для обеспечения корректной работы. [Ссылка на диаграмму компонентов и развёртывания](https://github.com/PahanHvesco/SkillCoder/blob/master/docs/diagrams/deployment.png).
