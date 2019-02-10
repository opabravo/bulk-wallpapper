# About bulk-wallpapper
Bulk download wallpappers from wallhaven.cc

#Usage
Usage: ./wallhaven.sh [OPTIONS]
Download wallpapers from wallhaven.cc

If no options are specified, default values from within the script will be used

 -l, --location         location where the wallpapers will be stored
 -n, --number           Number of Wallpapers to download
 -s, --startpage        page to start downloading from
 -t, --type             Type of download Operation: standard, search,
                        favorites, useruploads
 -c, --categories       categories to download from, eg. 111 for General,
                        Anime and People, 1 to include, 0 to exclude
 -f, --filter           filter out content based on purity rating, eg. 111
                        for SFW, sketchy and NSFW content, 1 to include,
                        0 to exclude
 -r, --resolution       resolutions to download, separate mutliple
                        resolutions by ,
 -g, --atleast          minimum resolution, show all images with a
                        resolution greater than the specified value
                        do not use in combination with -r (--resolution)
 -a, --aspectratio      only download wallpaper with given aspectratios,
                        separate multiple aspectratios by ,
 -m, --mode             sorting mode for wallpapers: relevance, random,
                        date_added, views, favorites
 -o, --order            order ascending (asc) or descending (desc)
 -b, --favcollection    name of the favorite collections to download
 -q, --query            search query, eg. 'mario', single quotes needed,
                        for searching exact phrases use double quotes
                        inside single quotes, eg. '"super mario"'
 -d, --dye, --color     search for wallpapers containing the given color,
                        color values are RGB without a leading #
 -u, --user             download wallpapers from given user
 -p, --parallel         make use of gnu parallel (1 to enable, 0 to disable)
 -v, --version          show current version
 -h, --help             show this help text and exit
