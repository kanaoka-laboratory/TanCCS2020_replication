Tanらの研究＠CCS2020システムの日本語化
====
Tanらの実験に用いたシステムとサーベイ内容を日本語化して追試実験を実施した。

## Tanらの実験システムの日本語化
Githubに公開されているシステム（ https://github.com/cupslab/password_meter ）を用い、表現の翻訳や文章構造の修正を行った。

### パスワード作成時に表示される文章の翻訳一覧表

パスワードを生成する際にシステムにより表示される可能性のある文章の一覧である。原文と日本語訳の双方を記載する。文章中に「〇」には数値や種別を示す単語など別途登録された用語が動的に入る。

|原文|日本語訳|
----|----
|Avoid using dates | 日付の使用は避けてください |
|The way you structure your password is predictable | パスワードの構造は予測可能です|
|Avoid using dates like 〇 | 〇のような日付の使用は避けてください |
|Dates and years in any format are quite common in passwords | 任意の形式の日付と年はパスワードでとても一般的です |
|Avoid numerical patterns | 数値パターンは避けてください|
|Avoid numerical patterns like 〇 | 〇のような数値パターンは避けてください|
|Avoid patterns from the alphabet | アルファベットからのパターンを避けてください|
|Avoid patterns from the alphabet like 〇 | 〇のようなアルファベットのパターンを避けてください|
|Attackers know to guess sequences following the alphabet, in addition to repeated characters or patterns on your keyboard | 攻撃者は、キーボードで繰り返される文字やパターンに加えて、アルファベットに続くシーケンスを推測することを知っています |
|Don't use | 次のものは使用しないでください|
|, including simple transformations of those words/phrases where they substitute digits and symbols for letters | 、文字の代わりに数字や記号を使用する単語/フレーズの単純な変換を含む 
|or | 、|
|One technique attackers use is to try all possible passwords within common structures, or arrangements of character classes (e.g., where lowercase letters and digits are located) | 攻撃者が使用する1つの手法は、一般的な構造内、または文字クラスの配置（たとえば、小文字と数字が配置されている場所）内で可能なすべてのパスワードを試すことです 
|Attackers target their attacks to words used on a particular service | 攻撃者は、特定のサービスで使用される単語を攻撃の標的にします |
|Avoid strings of characters commonly found in passwords | パスワードで一般的にみられる文字列は避けてください |
|Attackers use software that automatically guesses millions of words commonly found in dictionaries, wordlists, or other people's passwords,publicText | 攻撃者は、辞書、単語リスト、または他の人のパスワードに一般的にみられる何百万もの単語を自動的に推測するソフトウェアを使用します |
|Your password is very easy to guess. | あなたのパスワードはとても簡単に推測できます|
|Your password could be better. | あなたのパスワードはもっと良くなります|
|Your password 〇 must | あなたのパスワードは〇以下の要件を満たす必要があります|
|Your password is pretty good. | あなたのパスワードはとても良いです|
|Use it only for this account.  | このパスワードは、このアカウントにのみ使用してください|
|Hide Password | パスワードを隠す|
|To make it even better | さらに良くするために|
|Your password appears strong. | あなたのパスワードは強力です|
|Don't reuse a password from another account! | 他のアカウントのパスワードを再利用しないでください！|
|Username | ユーザー名|
|password | パスワード|
|Show Password | パスワードの表示|
|Detailed Feedback | 詳細なフィードバック情報|
|Improve your password | パスワードを改善する|
|Why? | なぜ？|
|A better choice | より良い選択|
|How to make strong passwords | より強力なパスワードを作成するためには|
|Confirm Password | パスワードの確認|
|Doesn't match! | 一致していません！|
|Continue | 続行|
|Ways to Improve Your Password | パスワードを改善する改善する方法|
|names | 「名前」|
|pet names | 「ペットの名前」|
|common phrases | 「一般的なフレーズ」|
|dictionary words | 「辞書の単語」|
|words used on Wikipedia | 「ウィキペディアで使用されている単語」|
|simple transformations of words or phrases | 「単語やフレーズの単純な変換」|
|characters | 文字以上|
|Contain a symbol | 記号を含む|
| and a symbol | および記号|
|Contain a digit | 数字を含む|
| and a digit | および数字|
|Contain an uppercase letter | 大文字を含む|
| and an uppercase letter | および大文字|
| and a lowercase letter | 小文字を含む|
|Contain a lowercase letter | および小文字|
|Consider using more uppercase letters | より多くの大文字を使用することを検討してください|
|See Your Password With Our Improvements | パスワードと改善点を表示する|
|Tips to make a stronger password | より強力なパスワードを作成するためのヒント|
|Making a Strong Password | 強力なパスワードの作成|
|Strategies for Making a Strong Password | 強力なパスワードのを作成するための戦略|
|This is a demo meter.Please don't type in your real password. | これはデモメーターです。実際に利用しているパスワードは入力しないでください。|
|The password policy enforced by this meter requirespasswords to contain a minimum of 12 characters,not be found in previous password leaks,and to be estimated to withstand 10-10 guessing attempts. For more information, see here. | このメーターに適用されているパスワードポリシーでは、パスワードに最低12文字を含める必要があります。 また、これまでのパスワード漏洩したデータの中には見つかっていない必要があります。さらに、10^10回の推測攻撃に耐えられると推定される強度が求められます。詳細については、こちらを参照してください。|
|Do not reuse any of your existing passwords for any accounts you care about! Password reuse is very insecure! If it's too much to remember, write the passwords down in a secure place or use a password manager. | 大切なアカウントに既存のパスワードを再利用しないでください。パスワードの再利用は非常に危険です。覚えるパスワードが多すぎる場合は安全な場所に書き留めるか、パスワードマネージャーを利用してください。 |
|Attackers commonly try to log into many different websites with the usernames and passwords they obtain from other sites' data breaches. | 攻撃者は、他のサイトの情報漏洩により取得したユーザー名とパスワードを使用して、様々なWebサイトにログインしようとします。 |
|Make your password at least 12 characters,and consider including uppercase letters,digits, and/or symbols in unpredictable places. | パスワードは12文字以上にし、予測されない場所に大文字、数字、記号を含めることを検討してください。 |
|Attackers know that people often put numbers and symbols at the end of their password and uppercase letters at the beginning. Be different! | ユーザーがパスワードの末尾に数字や記号を付け、先頭に大文字を付けることがよくあることを、攻撃者は知っています。変えましょう！ |
|One way to make a strong password is to create a sentence that no one's ever said before and use the first letter or two of each word as your password, mixing in other types of characters. | 強力なパスワードを作成する1つの方法は、誰も言ったことのないような文章を作り、そこの単語の最初の1文字または2文字をパスワードとして使用し、他の種類の文字を混ぜることです。 |
|Consider using | 使用を検討してください|
|or more uppercase letters | 以上の大文字|
|Uppercase letters are surprisingly uncommon in passwords, which makes them hard to guess|パスワードでは大文字は驚くほど珍しいため、推測が困難です。|
|Attackers know that people often put numbers and symbols at the end of their password and uppercase letters at the beginning. Be different! | ユーザーがパスワードの末尾に数字や記号を付け、先頭に大文字を付けることがよくあることを、攻撃者は知っています。変えましょう！|
|Not repeat the same character 〇+ times in a row | 同じ文字を〇回以上続けて繰り返さない|
|One way to make a strong password is to create a sentence that no one's ever said before and use the first letter or two of each word as your password, mixing in other types of characters. | 強力なパスワードを作成する1つの方法は、誰も言ったことのないような文章を作り、 そこの単語の最初の1文字または2文字をパスワードとして使用し、他の種類の文字を混ぜることです。|
|Avoid basing your password around the names of people or pets, things you like (e.g., favorite songs, cars),  sports, or birthdates. | 人やペットの名前、好きなもの(お気に入りの曲、車など)、スポーツ、生年月日などに基づいてパスワードを設定することは避けてください。|
|Many other people do the same, making it easy for attackers to guess. | ほかの多くの人も同じことをしているため、攻撃者が簡単に推測できます。|
|Not use a password found in previous security leaks | 以前の情報漏洩により取得されたパスワードを使用しない|
|Not base your password around your username | ユーザー名に基づいてパスワードを設定しない|
|Not be an extremely common password | とても一般的なパスワードではありません|
|Not include the following characters | 次の文字を含めないでください |
|Attackers are very good at guessing passwords under 10 characters even if the passwords look random | ランダムなパスワードに見えても、攻撃者は10文字未満のパスワードを推測する能力が上がっています|
|Not be an extremely common password | とても一般的なパスワードではありません|
|Not include the following characters | 次の文字を含めないでください|
|Make your password longer | パスワードを長くする|
|Make your password longer than 〇 characters | パスワードを〇文字より長くする|
|Attackers are very good at guessing passwords containing 12 characters or fewer,publicText | 攻撃者は12文字以下のパスワードを推測する能力が上がっています|
|Not contain the same character more than 〇＋ times | 同じ文字を〇回以上含まないでください |
|In recent years, attackers have gotten much better at guessing passwords under 16 characters | 近頃、攻撃者は16文字未満のパスワードを推測する能力が上がっています |
|Consider making your password longer than 〇 characters | パスワードを〇文字より長くすることを検討してください|
|aving variety in the types of characters you use makes your password harder to guess|使用する文字の種類が多様であると、パスワードを推測しにくくなります |
|Having variety in the types of characters you use makes your password harder to guess|使用する文字の種類が多様であると、パスワードを推測しにくくなります |
|Having variety in the types of characters you use makes your password harder to guess|使用する文字の種類が多様であると、パスワードを推測しにくくなります |
|Consider using more lowercase letters | より多くの小文字を使用することを検討してください|
| or more lowercase letters | 以上の小文字|
|Add 〇 in unpredictable locations | 予測不可能な場所に〇を追加することを検討してください|
|38\% of passwords contain only lowercase letters, making them easy for attackers to guess|パスワードの38\%には小文字しか含まれていないため、攻撃者は簡単に推測できます |
|Consider using more symbols | より多くの記号を使用することを検討してください|
|Add symbols in unpredictable locations | 予測できない場所に記号を追加する|
|Mix up your capitalization | 大文字を混ぜる|
|Because only 1\% of passwords use symbols, adding them unpredictably strengthens your password|パスワードの1\%のみが記号を使用しているため、それらを追加すると、パスワードが予期せず強化されます |
|Mix up your capitalization, rather than capitalizing everything|すべてを大文字にするのではなく、大文字を混ぜる |
|35\% of people also use only digits | 35\%の人が数字だけを使用しています|
|38\% of people also put digits at the end of the password|38\%の人がパスワードの末尾にも数字を入れています|
|Consider inserting digits into the middle | 中間に数字を挿入することを検討してください|
|Add characters other than digits to your password|数字以外の文字をパスワードに追加|
|Move symbols and digits earlier, rather than just at the end|記号と数字を末尾だけでなく、前にも移動する|
|Move symbols and digits elsewhere in your password|記号と数字をパスワードの別の場所に移動する|
|Few passwords contain symbols, which makes passwords with symbols harder to guess|記号を含むパスワードはほとんどないため、記号を含むパスワードを推測しにくくします。|
|21\% of passwords also contain only uppercase letters|パスワードの21\%に大文字のみが含まれています|
|Consider inserting digits into the middle, not just at the beginning|先頭だけでなく、中間に数字を挿入することを検討してください |
|10\% of people also put digits at the beginning of the password|10\%の人がパスワードの先頭にも数字を入れています |
|Move symbols and digits earlier, rather than just at the end|記号と数字を末尾だけでなく、前にも移動する|
|Move symbols and digits elsewhere in your password|記号と数字をパスワードの別の場所に移動する|
|Few passwords contain symbols, which makes passwords with symbols harder to guess|記号を含むパスワードはほとんどないため、記号を含むパスワードを推測しにくくします。 |
|21\% of passwords also contain only uppercase letters|パスワードの21\%に大文字のみが含まれています |
|Consider inserting digits into the middle, not just at the beginning|先頭だけでなく、中間に数字を挿入することを検討してください |
|10\% of people also put digits at the beginning of the password|10\%の人がパスワードの先頭にも数字を入れています |
|42\% of passwords contain only lowercase letters and number, making them easy for attackers to guess|パスワードの42\%には小文字と数字のみが含まれているため、攻撃者は簡単に推測できます |
|Capitalize a letter in the middle | 中間の文字を大文字にする|
|Capitalize a letter in the middle, rather than the first character|先頭の文字ではなく、中間の文字を大文字にする|
|30\% of people also capitalize only the first character|30\%の人が先頭の文字だけを大文字にします|
|Consider using more digits | より多くの数字を使用することを検討してください|
|Most passwords contain no digits or digits in predictable places; doing otherwise makes your password harder to guess|ほとんどのパスワードには、数字が含まれていなかったり、予測可能な場所に数字を含んでいます。それをやめればパスワードを推測しにくくなります|
|Add more letters and symbols to your password | パスワードにより多くの文字と記号を追加する|
|Consider inserting digits into the middle, not just at the end|数字を最後だけでなく、中間に挿入することを検討してください |
|Because keyboard patterns are very common in passwords, attackers know to guess them|キーボードパターンはパスワードでとても一般的であるため、攻撃者はそれらで推測することを知っています |
|Avoid using a pattern on your keyboard like 〇 | 〇のようなパターンをキーボードで使用しないでください|
|Avoid using a pattern on your keyboard | キーボードパターンの使用は避けてください|
|16\% of people also put symbols only at the end of the password|16\%の人がパスワードの末尾にのみ記号を付けています |
|Move your symbols earlier, rather than just at the end|記号を末尾だけでなく、前にも移動する|
|Don't use your account information in your password|パスワードにアカウント情報を使用しないでください|
|Avoid strings of characters commonly found in passwords like 〇|〇のようなパスワードで一般的にみられる文字列避けてください |
|Don't use your account information 〇 in your password|パスワードにアカウント情報〇を使用しないでください|
|Even if they don't make sense, these strings of characters show up in many passwords, which makes them bad to use in yours.|意味がない場合でも、これらの文字列は多くのパスワードでよくみられるため、パスワードでの使用には適していません |
|Don't repeat the same character many times in a row|同じ文字を連続して何度も繰り返さないでください|
|Attackers know to guess your username and email address as part of your password|攻撃者は、パスワードの一部としてユーザー名と電子メールアドレスを推測することを知っています|
|Have more variety in the characters you choose|選択する文字のバリエーションを増やす|
|Don't repeat the same character 〇 many times in a row|同じ文字〇を連続して何度も繰り返さないでください |
|Don't use site-specific terms in your password | パスワードにサイト固有の用語を使用しないでください|
|Have more variety than repeating the same 〇 | 同じ〇つの文字〇を繰り返すよりも多様性のあるものにしてください |
|Hitting the same key over and over adds little to your password's strength|同じキーを何度入力しても、パスワードの強度はほとんど向上しません |
|Avoid repeating sections | 文字列の繰り返しを避ける|
|Passwords that use only a few different characters are easy for attackers to guess|少数の文字のみを使用するパスワードは攻撃者が推測しやすいです |
|Avoid repeating sections 〇 | 〇のような文字列の繰り返しを避ける|
|Attackers frequently use other people's common passwords as a starting point for their guesses|攻撃者は、他の人の一般的なパスワードを推測の出発点として頻繁に使用します |
|In their guessing, attackers know to try duplicating parts of the password|攻撃者はパスワードの一部を複製して推測できることを知っています |
|, forwards or backwards | 、前方または後方|
|Avoid using very common passwords like 〇 as part of your own password|〇のようなとても一般的なパスワードの使用を避けてください |
|Avoid using very common passwords as part of your own password|自分のパスワードの一部として非常に一般的なパスワードを使用しないでください|

## Tanらのサーベイ文言の日本語化
実験参加者への説明文書や質問子を日本語に翻訳した。
