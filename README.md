# tilix-config

To dump Tilix setting from dconf and migrate settings use:

dconf dump /com/gexperts/Tilix/ > tilix.dconf

To load this file back into dconf on a different machine:

dconf load /com/gexperts/Tilix/ < tilix.dconf


