# pkgi-ps3-nopaystation

A [pkgi-ps3](https://github.com/bucanero/pkgi-ps3) database up to date with NoPaystation.

## Set up 

1. Copy the `dbformat.txt` from the repo to `/dev_hdd0/game/NP00PKGI3/USRDIR`
2. Create a `config.txt` file in `/dev_hdd0/game/NP00PKGI3/USRDIR` with :
```txt
language fr
filter EUR
dl_mode_background 1
url_games https://github.com/jy95/pkgi-ps3-nopaystation/releases/download/latest/pkgi_games.csv
url_dlcs https://github.com/jy95/pkgi-ps3-nopaystation/releases/download/latest/pkgi_dlcs.csv
url_demo https://github.com/jy95/pkgi-ps3-nopaystation/releases/download/latest/pkgi_demos.csv
url_themes https://github.com/jy95/pkgi-ps3-nopaystation/releases/download/latest/pkgi_themes.csv
url_avatars https://github.com/jy95/pkgi-ps3-nopaystation/releases/download/latest/pkgi_avatars.csv
```
3. Next time you open the app, you'll have an additional menu option Triangle called Refresh. When you select it, the local databases will be syncronized with the defined URLs.
4. Enjoy

If you prefer to use the Pending TSV Files instead, put the suffix `_pending` before the `.csv` extension like that in `config.txt` :

```txt
language fr
filter EUR
dl_mode_background 1
url_games https://github.com/jy95/pkgi-ps3-nopaystation/releases/download/latest/pkgi_games_pending.csv
url_dlcs https://github.com/jy95/pkgi-ps3-nopaystation/releases/download/latest/pkgi_dlcs_pending.csv
url_demo https://github.com/jy95/pkgi-ps3-nopaystation/releases/download/latest/pkgi_demos_pending.csv
url_themes https://github.com/jy95/pkgi-ps3-nopaystation/releases/download/latest/pkgi_themes_pending.csv
url_avatars https://github.com/jy95/pkgi-ps3-nopaystation/releases/download/latest/pkgi_avatars_pending.csv
```

Or if you want everything from NoPaystation (approved+pending), put the suffix `_all` before the `.csv` extension like that in `config.txt` :

```txt
language en
dl_mode_background 1
url_games https://github.com/Caio99BR/pkgi-ps3-nopaystation/releases/download/latest/pkgi_games_all.csv
url_dlcs https://github.com/Caio99BR/pkgi-ps3-nopaystation/releases/download/latest/pkgi_dlcs_all.csv
url_demo https://github.com/Caio99BR/pkgi-ps3-nopaystation/releases/download/latest/pkgi_demos_all.csv
url_themes https://github.com/Caio99BR/pkgi-ps3-nopaystation/releases/download/latest/pkgi_themes_all.csv
url_avatars https://github.com/Caio99BR/pkgi-ps3-nopaystation/releases/download/latest/pkgi_avatars_all.csv
```