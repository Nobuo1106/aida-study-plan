### 外部公開ブログで日々の進捗を記載してください

---

#### **HTML/CSSの勉強**
**目標**  
基本的なHTML、CSSを問題なく理解し、デザイナーの仕事を一部巻き取れるレベルの知識を身につける。

- **課題1**  
  以下のWebサイトをAIツールを利用せずに完コピしてください。Developerツールで確認は可ですが、コピペは禁止です。  
  全てのタグやセレクターの説明ができるようになることが目標です。なお、JSの動きの部分は無視して構いません。  
  [https://www.julianweidenthaler.com/](https://www.julianweidenthaler.com/)  
  - **期間**: 1週間  
  ※著作権の問題があるため、GitHubではなくzipファイルで提出してください。

- **課題2**  
  10個ほどバグが埋め込まれているHTMLファイルをお渡ししますので、すべて修正したPRを作成してください。  
  Chromeの拡張機能を利用するのは可ですが、AIツールの利用は禁止です。  
  - **期間**: 1日  

---

#### **Rubyのお勉強**
**目標**  
Railsで利用する基本的な構文を理解する。Railsで使用しないマイナーな文法は不要。

- **課題1**  
  実務で使えそうなGemを1つ作成してください。既存のGemと機能が重複していても構いません。  
  アイディア出しにはAIツールを使用可ですが、実装ではAIツールを使用しないでください。  
  全てのコードにコメントを付け、コードの内容を理解していることを示してください。また、口頭での説明の準備もしてください。  
  - **期間**: 1週間  

---

#### **Railsのお勉強**
**目標**  
実務で利用する基本的なパーツを自分で作成できるレベルを目指す。Railsアプリケーションの品質を高める価値を提供することが出来るようになること。

- **課題1**  
  RubyMineおよびVisual Studio Codeの両方でローカルのステップ実行ができる環境を構築してください。  
  - **期間**: 1日  

- **課題2**  
  サインアップ、サインアウト、サインインの機能をRSpecのカバレッジ100%で作成してください。AIツールの利用は禁止です。  
  - **期間**: 3日  

- **課題3**  
  サインアップ、サインアウト、サインインのAPIを作成してください。認証系APIの処理手順を理解することが目的のため、AIツールの利用は可とします。  
  テストはRapidAPIまたはPostmanを使用してください。こちらもRSpecのカバレッジ100%を達成してください。また、Helperを利用した場合のブランチと利用しないブランチの2つを作成してください。リポジトリは分けないでください。  
  - **期間**: 3日  

- **課題4**  
  課題2で作成したAPIでわざと異常系を発生させるために、Charlesを利用してリクエストを書き換えてください。テストケースに漏れがあった場合は課題2を修正してください。AIツールの利用は可とします。  
  - **期間**: 1日  

- **課題5**  
  FatControllerなプロジェクトをお渡しするので、リファクタリングしてください。  
  PR内にどこまでがControllerに含まれるべきか自分なりの意見を記載してください。  
  - **期間**: 3日  

- **課題6**  
  データベース設計が一部未完成のシンプルなブログアプリプロジェクトをお渡ししますので、以下を実施してください：  
  - ER図を作成し、`has_many`や`belongs_to`のリレーションを追加。  
  - 未完成のマイグレーションを完成させ、複合キーやデフォルト値を設定。  
  - Like機能など新規要件を追加し、スコープを活用したモデルを作成。  
  - **期間**: 3日  

---

#### **その他**
**目標**  
エンジニアとして必要なミドルウェアやツールの理解を深める。未経験のミドルウェアでも調べて利用できる能力を養い、デバッグができるようになる。

- **課題1**  
  DockerでRails環境を構築してください。Railsの課題1および課題2で作成したアプリケーションをそれぞれ別のDocker環境に移行してください。課題1および課題2とは別のリポジトリを作成し、READMEを記載して他の人が立ち上げられる手順を説明してください。手順書の作成にAIツールを使用することは可能ですが、再現性については自分で確認してください。  
  - **期間**: 5日  

- **課題2**  
  GitフローおよびGitHubフローを他のエンジニアにKeynoteを利用して説明し、承認をもらってください。エンジニアは旦那以外の経験者であれば誰でも構いません。エンジニア同士の交流を通じて協力してもらう経験を積むことが目的です。  
  - **期間**: 2日  

- **課題3**  
  Railsの課題2で作成したアプリケーションを用いて、JSとjQueryのAjaxを使用した画面を作成してください。画面のデザインは課題1と同じで構いません。JSとjQueryの実装はブランチで分けてください（リポジトリは分けないでください）。  
  - **期間**: 3日  

- **課題4**  
  スロークエリーが含まれるプロジェクトをお渡しします。EXPLAINを使用してボトルネックを解析し、RailsでIndexの付与や修正を行ってください。パフォーマンス計測のレポートを作成し、改善前後の結果を実証してください。AIツールの利用はドキュメントのみ可です。
  - **期間**: 2日  

- **課題5**  
  SQLインジェクションやXSSなどのセキュリティホールを含むプロジェクトをお渡しします。これを修正してPRを作成してください。その後、どのようなリスクがあったのかをマネージャーに報告するためのレポートを作成してください。実際に攻撃が可能なものは事例として紹介してください。レポートの作成にAIツールを使用することは可能ですが、口頭での説明責任があるため準備をしてください。  
  - **期間**: 4日  

--- 
  - **合計期間**: 45日（週6日実施したとして2ヶ月） 
  上記全てが終わった段階でエンジニアリングの中の草むしりに位は出来るようになっていると思います。本当はまだまだ適切なルーティングの設定、JSのDOM操作、SPA、SSL、WEBサーバーの設定、ログの設定、設計等ありますがキリがないのでこの辺でまあ良いかなと個人的には思います。これらはスキルが身についたとしても草むしりをやる気がないと意味がありません。これらのスキルを駆使して積極的にタスクを取りに行く姿勢を見せましょう。


---

### Post a daily report on public blog as well

---

#### **HTML/CSS Learning**
**Goal**  
To gain a solid understanding of HTML and CSS, enabling you to partially take over tasks typically done by designers.

- **Task 1**  
  Replicate the following website without using AI tools. Developer tools can be used for inspection, but direct copying is prohibited.  
  You should aim to explain every tag and selector used. Ignore JavaScript behavior.  
  [https://www.julianweidenthaler.com/](https://www.julianweidenthaler.com/)  
  - **Duration**: 1 week  
  *Note*: Due to copyright concerns, submit the project as a zip file instead of uploading it to GitHub.

- **Task 2**  
  You will be provided with an HTML file containing around 10 embedded bugs. Fix all issues and create a pull request.  
  Chrome extensions may be used for debugging, but AI tools are not allowed.  
  - **Duration**: 1 day  

---

#### **Ruby Learning**
**Goal**  
To understand fundamental Ruby syntax used in Rails. Rarely used or niche syntax is not required.

- **Task 1**  
  Create a practical Gem that could be used in real-world scenarios. Overlapping functionality with existing Gems is acceptable.  
  You may use AI tools for ideation but not for implementation.  
  Add comments to all code to demonstrate your understanding and prepare for verbal explanation.  
  - **Duration**: 1 week  

---

#### **Rails Learning**
**Goal**  
To develop the skills to independently create basic components used in real-world Rails applications, and to deliver value by improving application quality.

- **Task 1**  
  Set up local step execution environments in both RubyMine and Visual Studio Code.  
  - **Duration**: 1 day  

- **Task 2**  
  Implement signup, signout, and signin functionalities with 100% RSpec coverage. AI tools are not allowed.  
  - **Duration**: 3 days  

- **Task 3**  
  Create APIs for signup, signout, and signin. The goal is to understand the processing steps for authentication APIs. AI tools can be used.  
  Use RapidAPI or Postman for testing. Achieve 100% RSpec coverage.  
  Create two branches: one using Helpers and one without, but avoid creating separate repositories.  
  - **Duration**: 3 days  

- **Task 4**  
  Use Charles to manipulate requests and deliberately introduce abnormal scenarios for the APIs created in Task 2.  
  Fix any uncovered test case gaps in Task 2. AI tools can be used for this task.  
  - **Duration**: 1 day  

- **Task 5**  
  Refactor a provided FatController project.  
  In your pull request, include your perspective on what should belong in a Controller.  
  - **Duration**: 3 days  

- **Task 6**  
  Work on an incomplete simple blog app project provided to you. Complete the following tasks:  
  - Create an ER diagram and add `has_many` and `belongs_to` relationships.  
  - Complete unfinished migrations, including compound keys and default values.  
  - Add a Like feature and implement model scopes to query data.  
  - **Duration**: 3 days  

---

#### **Others**
**Goal**  
To understand middleware and tools essential for engineering, and to develop the ability to research and use unfamiliar tools effectively. Be able to debug at a minimum.

- **Task 1**  
  Set up a Docker environment for Rails.  
  Migrate the apps created in Rails Tasks 1 and 2 into separate Docker environments.  
  Create a new repository for each and write clear README instructions for others to follow. AI tools can be used for writing documentation, but verify its reproducibility yourself.  
  - **Duration**: 5 days  

- **Task 2**  
  Use Keynote to explain Git Flow and GitHub Flow to another engineer, and obtain their approval.  
  Collaborating with experienced engineers (other than your mentor) is required to build communication skills vital for engineering.  
  - **Duration**: 2 days  

- **Task 3**  
  Use the Rails app from Task 2 to create a frontend using JS and jQuery with Ajax.  
  The design should match Task 1's specifications.  
  Separate implementations using JS and jQuery into branches (not repositories).  
  - **Duration**: 3 days  

- **Task 4**  
  Analyze and fix bottlenecks in a provided project containing slow queries.  
  Use EXPLAIN to identify issues, and optimize queries with appropriate indexing in Rails.  
  Provide a report detailing pre- and post-optimization performance improvements. AI tools are allowed for documentation.  
  - **Duration**: 2 days  

- **Task 5**  
  Fix security vulnerabilities like SQL injection and XSS in a provided project.  
  Submit a pull request with your fixes.  
  Write a report explaining the risks and real-world implications of the vulnerabilities.  
  Demonstrate actual attacks where feasible. AI tools can assist with writing, but prepare to explain your work verbally.  
  - **Duration**: 4 days  

---

- **Total Duration**: 45 days (approximately 2 months with 6-day weeks)  
After completing these tasks, you should be capable of handling foundational engineering tasks ("weeding the garden," so to speak). While this plan doesn’t cover advanced topics like routing optimization, DOM manipulation, SPA development, SSL configuration, web server setup, logging, and system design, it provides a solid base.  

Remember, technical skills alone are insufficient if you lack the drive to take on tasks proactively. Use these skills to actively seek out challenges and contribute effectively to your team.