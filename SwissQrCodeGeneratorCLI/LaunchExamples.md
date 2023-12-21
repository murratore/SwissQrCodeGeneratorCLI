# With valid Reference Number
--amount 390 --iban CH4431999123000889012  --currency CHF --language DE --format SVG --outputsize QrBillOnly --message "Rechnung für xy" --reference "210000000003139471430009017" --creditor_name "Hans Muster" creditor_address1 "Musterweg 10" --creditor_address2 "8000 Zürich" --creditor_countrycode "CH" --savepath "C:\temp\qrcode.svg"

# No Reference Number needed
--amount 390 --iban CH0509000000150964595 --currency CHF --language DE --format SVG --outputsize QrBillOnly --message "Rechnung für xy" --creditor_name "Hans Muster" creditor_address1 "Musterweg 10" --creditor_address2 "8000 Zürich" --creditor_countrycode "CH" --savepath "C:\temp\qrcode.svg"
