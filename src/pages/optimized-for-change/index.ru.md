---
title: С заделом на будущее
date: '2018-12-12'
spoiler: Чем отличается хороший API от классного?
---

Чем отличается хороший API от классного? Действительно *хороший* API <s>трудно найти, легко потерять и невозможно забыть</s> [ну вы поняли](https://blog.codinghorror.com/falling-into-the-pit-of-success/).

Читаемость, производительность, минимум подводных камней — про такие вещи думаешь в первую очередь. Я поэтому называю их дизайном «первого порядка». Без них тяжело. Иногда приходится чем-то жертвовать, но это делаешь осознанно.

Однако, код — это живой артефакт и вечный черновик. Как правило, он не пишется однажды, а постоянно дописывается и переписывается разными людьми. Никогда не знаешь, что в итоге получится.

Я заметил, что лучших API-дизайнеров, с которыми мне повезло пообщаться, объединяет одна черта. Они уделяют должное внимание дизайну «первого порядка», но на этом не останавливаются. Вместо этого они погружаются с головой в дизайн «второго порядка»: **как именно код, использующий этот API, будет меняться со временем**.

Самая элегантная абстракция может рассыпаться от одного нового требования. *Классные* API прогнутся, но не треснут. Они готовы к тому, что ты будешь двигать код, что-то переименовывать, абстрагировать повторяющуюся логику, развинчивать плохую абстракцию в копипасту, добавлять хак или переписывать глючный модуль.

Классные API работают не только сегодня, но и шесть месяцев спустя. Они придуманы с заделом на будущее.