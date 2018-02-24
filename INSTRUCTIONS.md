  
  Some strings have variables in them. They are marked by curly braces e.g. {variable}.
  
  Example: 
  
  `"trade.title-local-buy": "Buying {amountXmr} XMR for {amountFiat} {currency}"`

  After translation:
  
  `"trade.title-local-buy": "Покупка {amountXmr} XMR за {amountFiat} {currency}"`
  
  Some parts of the text strings need to be formatted as (for example) links, so they are stored as separate variables. 
  
  Here's an example: 
  
  `"post-ad.logged-out-notice": "In order to post a new ad please {log-in} or {sign-up}",
  "post-ad.logged-out-notice-log-in": "log in",
  "post-ad.logged-out-notice-sign-up": "sign up"`
  
  After translation it should like this: 
  
  `"post-ad.logged-out-notice": "Чтобы создать объявление, {log-in} или {sign-up}",
  "post-ad.logged-out-notice-log-in": "войдите",
  "post-ad.logged-out-notice-sign-up": "зарегистрируйтесь"`
  
  Also some strings have HTML tags in them. They need to be preserved in the relevant place.
  
  Example:
  
  `"trade.status.not-escrowed-text-0": "This trade is <strong>not escrowed</strong>."`

  After translation:
  
 `"trade.status.not-escrowed-text-0": "Эта сделка <strong>не защищена депонированием</strong>."`

  Please refer to existing language files as examples of the translation format.
