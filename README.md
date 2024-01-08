Для подготовки датасета нужно открыть терминал в папке с фото/видео

Для видео
```
python Путь/instant-ngp-master/scripts/colmap2nerf.py --video_in Название видеофайла --video_fps 10 --run_colmap --aabb_scale 16
```
Для фото
```
python Путь/instant-ngp-master/scripts/colmap2nerf.py --colmap_matcher exhaustive ---run_colmap --aabb_scale 16 --images Название 
```
