get_product_list(page, campaign_id, access_token) - получает список товаров из API Яндекс Маркета на основе указанного ID кампании и токена доступа. Функция возвращает JSON-объект с результатом.

update_stocks(stocks, campaign_id, access_token) - обновляет уровни остатков для набора товаров в API Яндекс Маркета на основе указанного ID кампании и токена доступа. Функция возвращает JSON-объект с результатом.

update_price(prices, campaign_id, access_token) - обновляет цены для набора товаров в API Яндекс Маркета на основе указанного ID кампании и токена доступа. Функция возвращает JSON-объект с результатом.

get_offer_ids(campaign_id, market_token) - получает ID предложений для заданного ID кампании и маркет-токена. Функция возвращает список ID предложений.

create_stocks(watch_remnants, offer_ids, warehouse_id) - создает список уровней остатков для набора товаров на основе указанных остатков, ID предложений и ID склада. Функция возвращает список уровней остатков.

create_prices(watch_remnants, offer_ids) - создает список цен для набора товаров на основе указанных остатков и ID предложений. Функция возвращает список цен.

async def upload_prices(watch_remnants, campaign_id, market_token) - загружает цены для набора товаров в API Яндекс Маркета на основе указанных остатков, ID кампании и маркет-токена. Функция возвращает список цен.

async def upload_stocks(watch_remnants, campaign_id, market_token, warehouse_id) - загружает уровни остатков для набора товаров в API Яндекс Маркета на основе указанных остатков, ID кампании, маркет-токена и ID склада. Функция возвращает два списка уровней остатков: один с ненулевыми уровнями остатков и один со всеми уровнями остатков.
