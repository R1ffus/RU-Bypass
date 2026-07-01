# RU-Bypass Production Edition

## Что включено в production
- local/private networks
- статические IP для Госуслуг и Ozon
- Госуслуги, nalog.ru, mos.ru
- банки
- маркетплейсы и классифайды
- доставка и логистика
- операторы связи
- РЖД
- Steam как latency-sensitive исключение
- hh.ru

## Что вынесено в optional

### Экосистемы
- Yandex
- Mail.ru
- VK / OK / CDN

Причина: большие экосистемы с широкой поверхностью трафика. Их лучше подключать осознанно.

### Медиа и вспомогательные сайты
- Kinopoisk / IVI / Okko / more.tv / Rutube
- Gismeteo / 2ip

Причина: не критичны для базовой production-схемы и могут быть добавлены отдельным пакетом.

## Рекомендуемый порядок
1. Загрузить `ru-bypass-production.txt`
2. Detect / Apply
3. Проверить:
   - gosuslugi.ru
   - online.sberbank.ru
   - ozon.ru
   - rzd.ru
   - steampowered.com
4. Если нужно — добавить:
   - `ru-bypass-optional-ecosystems.txt`
   - `ru-bypass-optional-media.txt`
