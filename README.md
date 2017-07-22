# solandinas-smtp-relay

To run a SES SMTP RELAY

```
docker run -d --name ses-relay -e SMTP_USERNAME=AKIAJVDMXZEY7MDK5RZQ -e SMTP_PASSWORD=AmFD7SJoaO3et9mXLyAmaMMFNFIV8Ny0JOa4E+PvuvIX -e DC_RELAY_NETS=190.41.153.152 -p 25:25  building5/ses-relay
```
