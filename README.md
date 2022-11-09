# uikit-under-the-hood

### pages 
- [RunLoop](runloop.md)
 
- Multithreading (async/await in advanced-swift)
  - [GCD](runloop.md)
  - [Operations](runloop.md)
  - [Responder Chain](responder-chain.md)

### CoreAnimation 
По сути UIView проксирует все необходимые в CALayer. Когда мы добавляем что-то на UIView,то добавляем новый слой. 
Это так же работает и в AppKit. 
- Изначально LayerKit.
- Отвечает за отрисовки всего в iOS приложении. 
- Изначально любое изменеие анимирует. 
- Нужно писать специальный код, чтобы отменить анимацию. 

### links
https://habr.com/ru/post/309506/ \
https://russianblogs.com/article/538471102/ \
https://habr.com/ru/company/otus/blog/590319/ \
https://habr.com/ru/post/464463/ \
https://www.youtube.com/watch?v=s8B6t5XnB7M
