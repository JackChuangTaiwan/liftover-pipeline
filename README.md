# liftover-pipeline

為了讓Windows的一般使用者也能在單機上使用liftover

我採用Picard tools 因為以下原因
 * crossmap 無法在windows環境下安裝
 * crossmap docker沒有介面，可能key錯檔案
 * Jupiter notebook docker版本有token問題我不會解
 * picard tool是Java基礎，編譯後可跨平台
 
 在這次pipeline中可以自動下載fasta 及 liftover 檔案及 picard
 
 稍做修正就可以服務其他版本轉換
 
 此外加入選擇檔案的功能，讓使用者可以不必手動key檔名
 
 搜尋資料夾中vcf功能可以批次處理資料夾中的VCF檔案
