# to find out the top 20 large files

sudo find / -type f -size +100M -exec du -h {} + | sort -hr | head -n 20
