## やったこと
- チュートリアル（最初のステップ、パスパラメータの実装）<br>
https://fastapi.tiangolo.com/ja/tutorial/path-params/<br>

  Github<br>
  https://github.com/konson-is/FastAPI

## Memo
- OpenAPI のドキュメントが自動生成される
- アノテーションを使用してパスパラメータの型宣言とバリデーションが可能
  ```python
  @app.get("/items/{item_id}")
  async def read_item(item_id: int):
      return {"item_id": item_id}
  ```
- pythonのasync await触ってみる

