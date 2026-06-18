# ref-script

constants/
|       Fichier                |           Classes           |          Fonctions          |
|------------------------------|-----------------------------|-----------------------------|
|       constant.py            |variable :STORE_ID_COLUMN / FILE_COLUMNS / SYNC_FIELDS /   |  
|                              |SCHEDULE_COLUMNS /CLIENT_COLUMN_RENAME / OPTIONAL_COLUMNS/ | 
|                              |RESULT_COLUMNS / STATUS_OPEN / STATUS_CLOSED / OUTPUT_DIR/ |
|                              |EXPORT_ACTION_MAP /OUTPUT_RESULTAT / OUTPUT_LOG /          |
|                              |DEFAULT_COMPARE_OUTPUT / DEFAULT_VALIDATE_OUTPUT /         |
|                              |ACTION_NO_CHANGE / ACTION_UPDATE / ACTION_CREATE /         |
|                              |ACTION_CLOSE / ACTION_COLUMN                               | 
normalize/ 
|       Fichier                |           Classes           |          Fonctions          |
|------------------------------|-----------------------------|-----------------------------|
|      file_loader.py          |-LoadError                   | - _is_client_format()        |
|                              |                             | - _find_data_sheet()         | 
|                              |                             | - _normalize_raw_dataframe() |
|                              |                             | - load_store_file()          |