```python
import pygame as pg

pg.font.init()
FPS = 60
WIDTH, HEIGHT = 700, 584
WIN = pg.display.set_mode((WIDTH, HEIGHT))
clock = pg.time.Clock()


#constants


#variables




def draw_update():
    clock.tick(FPS)
    pg.display.flip()
    WIN.fill((0, 0, 0))


while True:
    for event in pg.event.get():
        if event.type == pg.QUIT:
            pg.quit()
            break
    #code here
    
    
    
    
    
    draw_update()
```
