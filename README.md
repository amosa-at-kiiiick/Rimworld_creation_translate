# RimWorld 角色姓名 繁體中文化
此專案提供遊戲 `RimWorld` 中各種角色的名稱、姓氏與暱稱繁體中文化版本的資源包
並且同時提供原文檔案歡迎社群共同提供翻譯。

### 如何安裝
直接下載此份文件後，將`resources.assets`這個檔案 複製並覆蓋到 
RimWorld安裝資料夾中的 `\RimWorldWin_Data\resources.assets` 
通常目錄位置會在: 
*D:\SteamLibrary\steamapps\common\RimWorld\RimWorldWin_Data\resources.assets*

>此專案主線(master)將會盡快依照當前RimWorld正式遊戲版本為主，
如有特別版本需求請切換至對應版本的分支下載。

### 如何提供翻譯協助
首先感謝您伸出援手相助，阿MOSA我已經初步有匯入網路上資源找到的英文名中翻的資料匯入先，
只要有社群提供更新，阿MOSA我會盡快校對整理後，將新的檔案打包並釋出。
不過最主要為`rimworld_creations.txt`這份檔案內容比較複雜，特別提出來解釋一下翻譯需求，
以下大概列出此檔案的XML格式
```
<PlayerCreatedBios>
	<PawnBio>
		<Name>
			<First>需要翻譯區 James</First>
			<Last>需要翻譯區 Grey</Last>
			<Nick>需要翻譯區 Doc</Nick>
		</Name>
		<Gender>Male</Gender>
		<PirateKing>True</PirateKing>
		<Childhood>
			<Title>需要翻譯區 Fallen prodigy</Title>
			<TitleShort>需要翻譯區 Prodigy</TitleShort>
			<BaseDesc>需要翻譯區 Some desc....  </BaseDesc>
			<WorkDisables>
				<li>Social</li>
			</WorkDisables>
			<SkillGains>
				<li>
					<key>Construction</key>
					<value>2</value>
				</li>
			</SkillGains>
		</Childhood>
		<Adulthood>
			<Title>需要翻譯區 Mad scientist</Title>
			<TitleShort>需要翻譯區 Scientist</TitleShort>
			<BaseDesc>需要翻譯區 Some desc.... </BaseDesc>
			<WorkDisables>
				<li>Hauling</li>
				<li>Mining</li>
			</WorkDisables>
			<SkillGains>
				<li>
					<key>Research</key>
					<value>5</value>
				</li>
			</SkillGains>
			<SpawnCategories>
				<li>Raider</li>
				<li>Traveler</li>
			</SpawnCategories>
			<BodyNameGlobal>Thin</BodyNameGlobal>
		</Adulthood>
	</PawnBio>
<PlayerCreatedBios>
```
需要翻譯的標籤大概整理如下:
- ``<Title>``
- ``<TitleShort>``
- ``<First>``
- ``<Last>``
- ``<Nick>``
- ``<BaseDesc>`` `要特別注意全大寫的單字為系統變數，請勿修改。(如 NAME HE HISCAP ...)`

### 社群協助感謝名單 :D :D :D 
阿MOSA將會將您的每一筆貢獻放入在此列表中，感謝大家的付出 :D
- 阿MOSA實況台 [twitch.tv/amosa2001](https://twitch.tv/amosa2001)
