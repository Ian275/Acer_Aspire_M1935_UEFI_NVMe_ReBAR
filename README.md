# IPIMB-AR_P11-B1_UEFI
Acer IPIMB-AR_P11-B1_Update

BIOS version: P11-B1

可支援顯示卡 UEFI 啟動和 Secure boot<br>
支援 NVMe 啟動<br>
[來源](https://winraid.level1techs.com/t/howto-get-full-nvme-support-for-all-systems-with-an-ami-uefi-bios/30901)
加入由 xCuri0 製作的 [ReBarDxe](https://github.com/xCuri0/ReBarUEFI) ，可啟用 Resizable BAR<br>
開啟 Resizable BAR 需要啟用 [Above 4G Decoding](https://github.com/xCuri0/ReBarUEFI/wiki/Enabling-hidden-4G-decoding)<br> 
VarOffset: 0x1<br>
![VarOffset: 0x1](https://github.com/Ian275/Ian2561376/blob/main/VarOffset_0x1.png)

只有 "P11-B1_Original.rom" 可以使用 AFUWINGUI.exe 燒錄<br>
使用 AFUWINGUI.exe 燒錄要選擇 "Program ALL Blocks" 否則會失敗！<br>
![Program ALL Blocks](https://github.com/Ian275/Acer_Aspire_M1935_UEFI_NVMe_ReBAR/blob/main/afuwin.png)<br>
![FLASH](https://github.com/Ian275/Acer_Aspire_M1935_UEFI_NVMe_ReBAR/blob/main/afuwinflash.JPG)

燒錄前請先檢查CMOS電池是否安裝並且有電，否則可能會燒錄失敗！

此 BIOS 非完整的 BIOS ，請不要直接使用燒錄器(CH341A等燒錄器)燒錄！
<br>
<br>
(Boot with Intel Iris Xe Graphics 80 EU (DG1))
![DG1](https://private-user-images.githubusercontent.com/184845667/376045663-18c44b5f-3a7d-434f-b7e1-2f81ebbc21ab.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mjk0MDM1ODQsIm5iZiI6MTcyOTQwMzI4NCwicGF0aCI6Ii8xODQ4NDU2NjcvMzc2MDQ1NjYzLTE4YzQ0YjVmLTNhN2QtNDM0Zi1iN2UxLTJmODFlYmJjMjFhYi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMDIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTAyMFQwNTQ4MDRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT04YWQ3OWU5YWE4OTk1ZWU5MDU0ZjVjODQxYzZjOGIwOWZlYzgxN2NmNDFkYjQyM2UwMjFhODBkOGUzMTZlYjdmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.rOh7OFCKDCZad_O3rBWyLJdEpZCljHrxSghJNM-20ZQ)
