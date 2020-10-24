# WoW Calendars

An unofficial list&mdash;and personal interpretation&mdash;of calendar systems in the **World of Warcraft** serialised for use with [wowcal](https://github.com/onoira/wowcal).

## Contributing

Forking is encouraged. Refer to the **wowcal** `schema.json`.

You can validate the YAML using the included validation script:

    # Clone the 'wowcal' repository:
    git clone https://github.com/onoira/wowcal
    cd wowcal

    # Install requirements:
    setup.py egg_info
    cat ./wowcal.egg-info/requires.txt | sed -e "s/\[.*\]//" > requirements.txt
    pip3 install -r requirements.txt

    # Run the validator:
    validate.py path/to/file.yml

## References

- ["Timeline"](https://wow.gamepedia.com/Timeline). Wowpedia.
- ["Calendars of Azeroth"](https://web.archive.org/web/20201024144003/https://moon-guard.fandom.com/wiki/Calendars_of_Azeroth). [Moon Guard](https://moon-guard.fandom.com/wiki/) (US) and **Earthen Ring** (US) wikis.
- A tonne of cross-referenced articles

## License

[CC0-1.0](LICENSE)
