# FTP

`FTP` ( `File Transfer Protocol` ，即文件傳輸協議)是 `TCP/IP` 協議組中的協議之一。 `FTP` 協議包括兩個組成部分，其一爲 `FTP` 服務器，其二爲 `FTP` 客戶端。其中 `FTP` 服務器用來存儲文件，用戶可以使用 `FTP` 客戶端通過 `FTP` 協議訪問位於 `FTP` 服務器上的資源。在開發網站的時候，通常利用 `FTP` 協議把網頁或程序傳到 `Web` 服務器上。此外，由於 `FTP` 傳輸效率非常高，在網絡上傳輸大的文件時，一般也採用該協議。

默認情況下 `FTP` 協議使用 `TCP` 端口中的 `20` 和 `21` 這兩個端口，其中 `20` 用於傳輸數據， `21` 用於傳輸控制信息。但是，是否使用 `20` 作爲傳輸數據的端口與 `FTP` 使用的傳輸模式有關，如果採用主動模式，那麼數據傳輸端口就是 `20` ；如果採用被動模式，則具體最終使用哪個端口要服務器端和客戶端協商決定。