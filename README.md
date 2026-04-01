しょぼんのアクション(Syobon no action/Syobon action/Cat Mario)をHTML+JSに移植します  
本家のソースコードなどに含まれていたものを使っています  
  
移植するうえで使用したモデルは  
GeminiとClaudeです。  
  
ちなみに部分的に改変が含まれています  
例えば、メッセージボックス(ストップ処理のロジック)やエンドロール(内容)です 
  
Cladue→Geminiに分析→Claude→Geminiに受け渡し→Gemini（別セッション）→Gemini→Gemini（別セッション）→Gemini→Claude→Gemini→…  
といった感じに作成しました

本家のREADMEはりーどみー.txtにあるよ

原作著作者：ちく

I am porting Syobon no Action (Syobon action/Cat Mario) to HTML+JS.
I am using assets and code from the original source.

The models I used for this porting project are Gemini and Claude.

Note that I have made some modifications to the original.
For example, the message box (stop processing logic) and the ending credits (content).

The creation process went like this:
Claude → Gemini for analysis → Claude → Gemini → Gemini (separate session) → Gemini → Gemini (separate session) → Gemini → Claude → Gemini → …

The original README is in "りーどみー_en.txt".
I had Gemini translate the "readme.txt" file into other languages on its own.
※The contents are not translated at all, so plesae be careful.

Original author: tiku（ちく）

쇼본의 액션(Syobon no action/Syobon action/Cat Mario)을 HTML+JS로 이식합니다.
원작의 소스 코드 등에 포함되어 있던 것들을 사용하고 있습니다.

이식하는 과정에서 사용한 모델은 Gemini와 Claude입니다.

참고로 일부분에 개조된 내용이 포함되어 있습니다.
예를 들면 메시지 박스(정지 처리 로직)나 엔드롤(내용) 등입니다.

Claude → Gemini 분석 → Claude → Gemini 전달 → Gemini(다른 세션) → Gemini → Gemini(다른 세션) → Gemini → Claude → Gemini → …
와 같은 방식으로 제작했습니다.

원조 README는 りーどみー_ko.txt에 있어.
"readme.txt"의 타 언어 번역은 Gemini에게 알아서 시켰어요.
※내용은 전혀 번역 안 했으니까 주의해주새오

원작 저작자: 치쿠（ちく）
