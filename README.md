# video-amv-example
The examples of AMV video file

## Files
  * big_buck_bunny_240p.amv
  * sintel_2010_240p.amv
  * tos_240p.amv
  * spring_240p.amv
  * cosmos_laundromat_first_cycle_240p.amv
  * 01_llama_drama_240p.amv
  * 02_gran_dillama_240p.amv
  * 03_caminandes_llamigos_240p.amv
  * ed_240p.amv
  * glass_240p.amv
  * la_chute_d_une_plume_240p.amv
  * valkaama_320p.amv
  * route_66_an_american_baddream_320p.amv

## Flags (FFMPEG)

```
ffmpeg -i input.mov -vf crop=ih/3*4:ih,scale=320:240 -ac 1 -ar 22050 -r 25 -block_size 882 -filter:a "volume=5.0" output.amv
```

## Download link
https://drive.google.com/drive/folders/1oP4Blr10--mzeGohFScXymERnuqmQLIY?usp=sharing
