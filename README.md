﻿# TrendyolCase

## Kurulum

frontend-app klasöründe açılan terminalde

```bash
npm i
```

komutuyla node paketlerinin yüklenmesi gerekmektedir.

Angular frontend kodlarının .net tarafında bir kez güncellenmesi için

```bash
ng build --deploy-url /angular/libs/
```

komutu çalıştırılmalıdır.

Angular frontend kodlarının .net tarafında kod geliştirme sırasında güncellenmesi için

```bash
ng build --deploy-url /angular/libs/ --watch
```

komutu çalıştırılmalıdır.

IIS sunucu/proje run edilmelidir.
