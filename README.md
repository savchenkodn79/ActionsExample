# ActionsExample
TEST


<!-- curl --location --request POST 'http://dd.dmytro.in.ua/api/v2/import-scan/' \
--header 'Authorization: Token ${{ secrets.DD_TOKEN }}' \
--form 'engagement=10' \
--form 'verified=true' \
--form 'active=true' \
--form 'scan_type=SARIF' \
--form 'file=@./report.sarif' -->