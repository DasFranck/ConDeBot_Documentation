## Version 1.1 (2018/07/22)
- New plugins:
    - Roll: Roll the dices thanks to [dice library](https://github.com/borntyping/python-dice)
    - Prometheus (Still WIP): Prometheus metrics and monitoring
- Replier plugin
    - Lock function fixed
- Ops plugin
    - Ops file created if it doesn't exist
- More events handled by ConDeBot and Plugin classes, mainly related to reactions.

## Version 1.0 (2018/04/11)
- Bot rewrited
- Plugins can now reserve keywords
- Project's arborescence improved
- Ops are no longer stored by their nickdis but their snowflake
- Reserved keyword
- More verbose logs
- No more hardcoded paths in plugins
- Replier plugin
    - No longer triggered when action is a reserved keyword
- Ops plugin
    - Usage improved
    - Can op/deop by using user mention instead of his ID (Way more practical)
    - Rewrited in order to possibly implement non-global ops
    - Can now reload ops file
- Kaamelott plugin moved to legacy_files (be rewrited or deleted)
- Docker support and files added
- Travis files added
- UTF-8 forced everywhere
- Various fixs


## Version 0.2 (2017/03/16)
- Quick hotfix


## Version 0.1 (2017/02/06)
- Initial Release
