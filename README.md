Mets ça dans bashrc : 

sprite_sf=( $HOME/sprites-sf/*.txt  ) ; cat "${sprite_sf[RANDOM % ${#sprite_sf[@]}]}"
