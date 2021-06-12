# thread-safe-counter

- My OS environment : Ubuntu 18.04
- Project : Comparison between Semaphore & Mutex
  - file [tscounter.c] is using mutex, and file [sema_tscounter.c] is using semaphore


- Compare time
I executed each of files three times because their running time were flexible
  - Semaphore
  - ![스크린샷, 2021-06-12 21-25-10](https://user-images.githubusercontent.com/50763379/121775829-c9869100-cbc4-11eb-9546-eb383b07d3bc.png)

  - Mutex
  - ![스크린샷, 2021-06-12 21-26-44](https://user-images.githubusercontent.com/50763379/121775870-eb801380-cbc4-11eb-8dee-e3fa2439844e.png)

|Method|First|Second|Third|
|------|---|---|---|
|Sempahore|[4.976/2.171/5.414]|[5.015/2.122/5.500]|[5.116/2.397/5.349]
|Mutex|[0.191/0.249/0.124]|[0.143/0.208/0.069]|[0.181/0.240/0.113]

