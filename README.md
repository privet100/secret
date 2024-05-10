## Секретный чат и самоуничтожающиеся сообщения в Телеграм
* Создать секретный чат и включить самоуничтожение сообщений, как описано здесь https://lifehacker.ru/kak-sozdat-sekretnyj-chat-telegram/
* только на смартфоне, в десктопной версии Телеграмм этой функции нет
* только для общения двух людей
* все данные, переданные вне секретных чатов, сохраняются на серверах Телеграм, даже если пользователь удалит данные с телефона
 
## Восстановить аккаунт Телеграм, если сим-карта утеряна
* Заранее установтить в аккаунте Телеграм двухфакторную аутентификацию: мейл и пароль к Телеграм
* Вводить этот пароль вы будете нечасто, поэтому его очень легко забыть, так что лучше сохранить его в каком-нибудь надежном месте — например, в менеджере паролей
* Если Вы забудете этот облачный пароль к Телеграм
  + Вы можете отправить заявку на полное удаление аккаунта
  + через семь дней учетная запись удалится (со всеми контактами, чатами и подписками на каналы)
  + Вы сможете завести новый, совершенно пустой аккаунт на тот же номер телефона
  + другого способа восстановить аккаунт Телеграм с забытам паролем нет
* Позаботиться, чтобы никто не получил доступ к этому мейлу

## Второй аккаунт Телеграм
* Завести какую-нибудь сим-карту
  + возможно виртуальный номер телефона вместо настоящего мобильного
* Выучить наизусть номер телефона этой сим-карты
* Хранить саму сим-карту в надёжном месте, например, у кого-то из знакомых
* В приложении Телеграм завести второй аккаунт с этим номером телефона
* Выходить из второго аккаунта Телеграм каждый раз после использования
* При входе в аккаунт просить знакомого передать код (код будут запрашивать не каждый раз)
* Стирать каждый раз информацию о том, как знакомый передавал Вам код
* Можно облегчить вход в аккаунт, чтобы меньше беспокоить знакомого:
  + завести какой-нибудь мейл
  + выучить наизусть этот мейл и пароль от него
  + указать этот мейл в акаунте Телеграм
  + в этом случае код для входа в Телеграм будет приходить на мейл, а не на телефон знакомому (кажется иногда и на телефон, но чаще на мейл) (код будут запрашивать не каждый раз)
  + выходить из мейла каждый раз после использования
  + не сохранять в браузере этот мейл

## Идентификационный номер в Телеграм
* У каждого пользователя есть идентификационный номер (не связанный с номером телефона)
* Узнать свой идентицикацонный номер можно здесь @getmyid_bot
* Если злоумышленник отслеживает чаты с помощью программы и знает Ваш идентицикацонный номер, то у него есть информация о всех Ваших чатах и сообщениях, даже если Вы уже покинули эти чаты. Для этого злоумышленнику не обязательно знать Ваш номер телефона.

## IP-адрес в Телеграм
* Telegram может сообщать IP-адрес, например, по запросу правоохранительных органов
* Скрыть свой IP-адрес можно c помошью VPN

## Список контактов в Телеграм
* Если Вы устанавливаете в Телеграм опцию "Cинхронизировать контакты", то
  + ваши контакты из Телеграм копируются в Ваш аккаунт gmail
  + даже после выхода из аккаунта Телеграм или после удаления приложения Телеграм, Ваши контакты будут доступны в аккаунте gmail через телефон или компьютер
  + на серверы Телеграм попадают Ваши контакты из телефона, в том числе и контактная информация тех, кто не давал мессенджеру доступа к своим контактам, или вообще не пользуется Телеграм
    
## Безопасный мессенжер для компьютера uTox
* https://tox.chat/index.html
* если задать пароль, будет более высокий уровень конфиденциальности
* настройки Advanced
  + выключить протокол IPv6
  + включить протокол UDP для общения удалённо без возможности определения IP 
* не надо сохранять историю сообщений, тогда они будут исчезать каждый раз при закрытии чата
* безопасный сервис для передачи позывных https://pwpush.com/

## Безопасный мессенжер для смартфона Briar
* https://briarproject.org/

## gmail
* Установите двухэтапную идентификацию одним из следующих способов:
  + Электронный ключ
     - https://landing.google.com/advancedprotection/
  + Приложение Google Authenticator
  + 10 кодов (их надо сохранить в безопасном месте, например, у кого-то из знакомых)
  + Номер телефона (не стоит использовать этот способ, если есть риск потерять телефон вместе с компьютером)
  + Подтверждение через приглашение на телеофне (не стоит исполтьзовтать этот способ, если есть риск потерять телефон вместе с компьютером)
* Каждый раз после использования выходите из аккаунта
* Если вы удаляете какой-то мейл, то он не удаляется сразу окончательно, он попадает в корзину и его всё ещё можно прочитать в течение 30 дней или что-то около этого
  + чтобы окончательно удалить мейл, надо удалить его из корзины
* Имейте в виду, что здесь https://myactivity.google.com/myactivity сохраняется много информации
  
## Интернет-браузер
* Чтобы сохранить тайну истории просмотра страниц, можно сделать так: 
  + использовать отдельный браузер (Google chome, Firefox, Opera, ...) для просмотра конфиденциальной информации 
  + отключить в браузере сохранение истории просмотров
  + отключить сохранение куки
* Или так:
  + открывать вкладку "Инкогнито"
* Имейте в виду, что при использовании gmail и Google chrome здесь https://myactivity.google.com/myactivity сохраняется много информации

## История местоположения телефона
* Злоумышленник может получить доступ к истории местоположения телефона, если
  + на телефоне включено определение местоположения через gps
  + в аккаунте gmail включена опция "сохранять историю местороложения"
  + злоумышленник вошёл в Ваш gmail, используемый на телефоне (через телефон или компьютер)

<!-- TOC --><a name="welcome-to-the-app"></a>
## Если Вам нужна более подробная информация <img align="right" width="60" height="60" src="https://github.com/akostrik/stage_telegram/assets/22834202/9d78c9d6-c4c6-4566-9e83-3dcbc02e311e"> 
или здесь что-то недостаточно ясно описано, [напишите пожалуйста мне](mailto:stage.mongodb@gmail.com), я постараюсь узнать и понятным образом описать то, что нужно


  
