# Discord Adventure 爬蟲

透過爬蟲自動 輸入 `/adventure` 指令並參加討伐

 - ## 如何安裝

    **※ 需要 3.10 以上版本的 Python**

    Clone 這個專案，或是直接下載壓縮檔:

    ```sh
    git clone git@github.com:404-NOT-FUN/discord-adventure-crawler.git
    ```

    安裝執行環境:

    ```sh
    # 切換到專案目錄下
    cd .\discord-adventure-crawler\

    # 安裝 Poetry 環境管理套件
    pip install poetry

    # 安裝專案需要的套件
    poetry install
    ```

 - ## 如何使用
   直接執行 `run.bat` 或透過以下指令:

    ```sh
    # 切換到專案目錄下
    cd .\discord-adventure-crawler\

    # 執行主程式
    poetry run python DcCrawler.py
    ```

 - ## 參數調整
   - url
      - 使用指令的頻道 URL
   - wait_seconds
      - 登入畫面的最高停留時間，若超過時間還沒有進到指定url的就會timeout結束程式
   - 待補上
      - 待補上

 - ## 常見問題

    **Q: ?**

    **A:** !