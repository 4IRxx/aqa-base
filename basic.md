## База знаний

__Автоматизированное тестирование__ (_automated testing, test automation*_) — набор техник, подходов и инструментальных средств, позволяющий исключить человека из 
выполнения  некоторых задач в процессе тестирования. Тест-кейсы частично или полностью выполняет специальное инструментальное средство, однако разработка тест-кейсов, 
подготовка данных, оценка результатов выполнения, написания отчётов об обнаруженных дефектах — всё это и многое другое по-прежнему делает человек.

_*Test automation is the use of software to control the execution of tests, the comparison of actual outcomes to predicted outcomes,
the setting up of test preconditions, and other test control and test reporting functions. Commonly, test automation involves
automating a manual process already in place that uses a formalized testing process. (Ravinder Veer Hooda, An Automation of
Software Testing: A Foundation for the Future)_

__Автоматизированное тестирование программного обеспечения__ — часть процесса тестирования на этапе контроля качества в процессе разработки программного обеспечения. 
Оно использует программные средства для выполнения тестов и проверки результатов выполнения, что помогает сократить время тестирования и упростить его процесс. _[Wiki]_

Automation Testing is a software testing technique that performs using special automated testing software tools to execute a test case suite. 
On the contrary, Manual Testing is performed by a human sitting in front of a computer carefully executing the test steps.

The automation testing software can also enter test data into the System Under Test, compare expected and actual results and generate detailed test reports. 
Software Test Automation demands considerable investments of money and resources.

Successive development cycles will require execution of same test suite repeatedly. 
Using a test automation tool, it’s possible to record this test suite and re-play it as required. 
Once the test suite is automated, no human intervention is required. This improved ROI of Test Automation. 
The goal of Automation is to reduce the number of test cases to be run manually and not to eliminate Manual Testing altogether.

[Подробный туториал](https://www.guru99.com/automation-testing.html)

####  Автотесты можно условно разделить на три типа:

1. [Модульные (Unit)](https://habr.com/ru/articles/169381/)
2. [Интеграционные (API)](https://habr.com/ru/articles/556002/)
3. [end-to-end (UI/API)](https://habr.com/ru/companies/otus/articles/681066/)

Три этих типа условно образуют ["Пирамиду тестов"](https://habr.com/ru/articles/358950/)

#### Шаги автоматизации
##### Aston-версия:
1. Выбор тестового инструмента
2. Определение объема автоматизации
3. Планирование, дизайн и разработка
4. Выполнение теста
5. Техническое обслуживание

##### Другой вариант:
1. Determining the scope of test automation
2. Selecting the right automation tool
3. Test plan + Test design + Test strategy
4. Setting up the test environment
5. Automation test script development + Execution
6. Analysis + Generation of test results & test reports
[Подробный пошаговый разбор](https://testsigma.com/blog/automation-testing-life-cycle/)

Для бизнеса важно как можно скорее доставлять изменения пользовтелям, опережать конкурентов (CI/CD).
