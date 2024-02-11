#теха #версионирование 

Инструмент помогает версионировать большие объемы данных, а так же эксперименты и модели для ML. Работает поверх [[Git]]

> [!note]  Установка
> ```bash
> pip install dvc[all]
>```

> [!example] Как настроить соединение с Google Drive 
> ``` bash
>dvc remote add gdrive gdrive://1proKPxHsRecqmfhnuJ0iKeLbSnNI_nOR
>dvc remote modify gdrive gdrive_client_id 267252741611-7kqpvh6ichhqas3ejdi3tu8sm69192kp.apps.googleusercontent.com
>dvc remote modify gdrive gdrive_client_secret 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
>dvc remote modify gdrive gdrive_use_service_account true
>dvc remote modify gdrive --local gdrive_service_account_json_file_path dvc-test-414018-fda4a81ae428.json
>dvc push -r gdrive
>```
