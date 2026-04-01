しょぼんのアクション(Syobon no action/Syobon action/Cat Mario)をHTML+JSに移植します  
本家のソースコードなどに含まれていたものを使っています  
  
移植するうえで使用したモデルは  
GeminiとClaudeです。  
  
ちなみに部分的に改変が含まれています  
例えば、メッセージボックス(ストップ処理のロジック)やエンドロール(内容)です 
  
Cladue→Geminiに分析→Claude→Geminiに受け渡し→Gemini（別セッション）→Gemini→Gemini（別セッション）→Gemini→Claude→Gemini→…  
といった感じに作成しました

I am porting Syobon no Action (Syobon action/Cat Mario) to HTML+JS.
I am using assets and code from the original source.

The models I used for this porting project are Gemini and Claude.

Note that I have made some modifications to the original.
For example, the message box (stop processing logic) and the ending credits (content).

The creation process went like this:
Claude → Gemini for analysis → Claude → Gemini → Gemini (separate session) → Gemini → Gemini (separate session) → Gemini → Claude → Gemini → …
