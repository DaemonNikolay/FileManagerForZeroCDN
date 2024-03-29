# WPF

* **WPF** (*Windows Presentation Foundation*) - система, для построения клиентских приложений с визуально привлекательным пользовательским интерфейсом, подсистема в составе `.Net Framework`, использующая язык `XAML`.
* **XAML** (*eXtensible Application Markup Language*) - расширяемый язык разметки для приложений (основанный на `XML`). В `XAML` очень легко создавать, инициализировать и устанавливать свойства объектов с иерархическими отношениями.
* Особенности:
    1. Контроль внутри элемента управления (Позволяет определить контроль внутри другого элемента управления в качестве контента.);
    2. Привязка данных (Механизм для отображения и взаимодействия с данными между элементами пользовательского интерфейса и объекта данных на пользовательском интерфейсе.);
    3. Услуги СМИ(Предоставляет интегрированную систему для создания пользовательских интерфейсов с общими медиа-элементы, такие как изображения, аудио и видео.);
    4. Шаблоны (В WPF вы можете определить внешний вид элемента непосредственно с шаблоном);
    5. Анимации (Построение интерактивность и движение на пользовательском интерфейсе);
    6. Альтернативный вход (Поддерживает ввод мультитач на Windows 7 и выше.);
    7. Direct3D (Позволяет отображать более сложные графики и пользовательские темы);

***

# API

* **API** - это интерфейс для взаимодействия с процессом;

***

# Main Thread

* Главный поток, который выполняет метод `main()`, то есть главный метод программы. В рамках главного потока могут создаваться(запускаться) дочерние потоки (подпотоки), в которых, в свою очередь также могут запускаться потоки, и так далее. Главный поток от прочих потоков отличается тем, что создается первым;

***

# async/await 

* **Async** - указывает, что метод является асинхронным;
* **Await** - применяется к задаче в асинхронных методах, чтобы приостановить ваполняние метода до тех пор, пока эта задача не завершится. При этом выполнение потока не прерывается;

