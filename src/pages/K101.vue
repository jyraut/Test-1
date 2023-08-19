<template>
  <div :class="$style.k10">
    <div :class="$style.buttonoutlined">
      <div :class="$style.unstyledbutton">
        <div :class="$style.content">
          <div :class="$style.button">メディアを比較</div>
          <img :class="$style.maskedIcon" alt="" src="/masked-icon8.svg" />
        </div>
      </div>
    </div>
    <div :class="$style.bgParent">
      <div :class="$style.bg" />
      <div :class="$style.bg1" />
      <b :class="$style.b">フリーワード</b>
      <div :class="$style.textFieldoutlinedWrapper">
        <div :class="$style.textFieldoutlined">
          <div :class="$style.input">
            <div :class="$style.container">
              <div :class="$style.label">キーワードを入力</div>
            </div>
          </div>
        </div>
      </div>
      <b :class="$style.b1">メディア種別</b>
      <b :class="$style.b2">対応ファネル</b>
      <b :class="$style.b3">ターゲット</b>
      <b :class="$style.b4">ターゲット種別</b>
      <b :class="$style.b5">デモグラ</b>
      <div :class="$style.buttonoutlined1">
        <div :class="$style.unstyledbutton1">
          <div :class="$style.content">
            <img :class="$style.maskedIcon" alt="" src="/maskedicon1.svg" />
            <div :class="$style.button">ターゲットを選ぶ</div>
          </div>
        </div>
      </div>
      <div :class="$style.buttonoutlined2">
        <div :class="$style.unstyledbutton1">
          <div :class="$style.content">
            <img :class="$style.maskedIcon" alt="" src="/maskedicon1.svg" />
            <div :class="$style.button">メディア種別を選ぶ</div>
          </div>
        </div>
      </div>
      <b :class="$style.b6">主要広告主の業種/商材</b>
      <div :class="$style.buttonoutlined3">
        <div :class="$style.unstyledbutton1">
          <div :class="$style.content">
            <img :class="$style.maskedIcon" alt="" src="/maskedicon1.svg" />
            <div :class="$style.button">主要広告主の業種/商材を選ぶ</div>
          </div>
        </div>
      </div>
      <div :class="$style.buttonoutlined4">
        <div :class="$style.unstyledbutton1">
          <div :class="$style.content">
            <img :class="$style.maskedIcon" alt="" src="/maskedicon1.svg" />
            <div :class="$style.button">デモグラを選ぶ</div>
          </div>
        </div>
      </div>
      <b :class="$style.b7">下限費用感</b>
      <div :class="$style.chips1InputbTextOnlyA">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar15.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">toB</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA1">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar16.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">toC</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA2">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar17.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">両方</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.textFieldoutlinedParent">
        <div :class="$style.textFieldoutlined">
          <div :class="$style.input">
            <div :class="$style.container">
              <div :class="$style.label">選択してください</div>
            </div>
          </div>
        </div>
        <img
          :class="$style.arrowdropdownfilledIcon"
          alt=""
          src="/arrowdropdownfilled.svg"
        />
      </div>
      <div :class="$style.groupChild" />
      <b :class="$style.b8">ジャンル</b>
      <div :class="$style.groupItem" />
      <div :class="$style.groupInner" />
      <div :class="$style.rectangleDiv" />
      <div :class="$style.groupChild1" />
      <div :class="$style.groupChild2" />
      <div :class="$style.groupChild3" />
      <div :class="$style.groupChild4" />
      <div :class="$style.buttonoutlined5">
        <div :class="$style.unstyledbutton1">
          <div :class="$style.content">
            <img :class="$style.maskedIcon" alt="" src="/maskedicon1.svg" />
            <div :class="$style.button">ターゲットを選ぶ</div>
          </div>
        </div>
      </div>
      <div :class="$style.groupChild5" />
      <div :class="$style.chips1InputbTextOnlyA3">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar18.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">興味</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA4">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar19.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">認知</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA5">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar20.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">理解</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA6">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar21.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">購買 / 来店促進</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA7">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar22.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">推奨</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA8">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar23.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">リピート</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.groupChild6" />
      <div :class="$style.buttonoutlined6">
        <div :class="$style.unstyledbutton">
          <div :class="$style.button">検索条件をクリア</div>
        </div>
      </div>
      <div :class="$style.buttonoutlined7">
        <div :class="$style.unstyledbutton">
          <div :class="$style.button">検索する</div>
        </div>
      </div>
    </div>
    <div :class="$style.bgGroup">
      <div :class="$style.bg2" />
      <div :class="$style.unstyledbutton8">
        <img :class="$style.icon18" alt="" src="/icon8.svg" />
        <div :class="$style.button">お気に入り</div>
        <div :class="$style.unstyledbuttonChild" />
        <div :class="$style.button">10</div>
      </div>
      <div :class="$style.buttonoutlined8">
        <div :class="$style.unstyledbutton">
          <div :class="$style.button">お問い合わせ</div>
        </div>
      </div>
      <div :class="$style.bg3" />
      <div :class="$style.content6">
        <img :class="$style.maskedIcon1" alt="" src="/masked-icon9.svg" />
        <img :class="$style.icon18" alt="" src="/icon9.svg" />
        <div :class="$style.button10">比較</div>
      </div>
      <b :class="$style.title">MediaTitleMediaTitle</b>
      <div :class="$style.imageParent">
        <div :class="$style.image" />
        <img :class="$style.image2Icon" alt="" src="/image-2@2x.png" />
      </div>
      <div :class="$style.choiceChipbActiveWrapper">
        <div :class="$style.choiceChipbActive">
          <div :class="$style.avatar">
            <img :class="$style.maskedIcon" alt="" src="/avatar24.svg" />
          </div>
          <div :class="$style.label1">
            <div :class="$style.label2">ライフスタイル</div>
          </div>
          <div :class="$style.icon">
            <img :class="$style.icon1" alt="" src="/-icon.svg" />
          </div>
        </div>
      </div>
      <div :class="$style.description">
        <p :class="$style.p">1.食品・飲料 00%</p>
        <p :class="$style.p">2.家庭用品・トイレタリー 00%</p>
        <p :class="$style.p">3.化粧品 00%</p>
      </div>
      <div :class="$style.top3">広告主の業種/商材Top3</div>
      <div :class="$style.divider" />
      <div :class="$style.divider1" />
      <div :class="$style.divider2" />
      <div :class="$style.divider3" />
      <div :class="$style.divider4" />
      <div :class="$style.div1">メディア概要</div>
      <div :class="$style.div2">メディア種別</div>
      <div :class="$style.description1">ポータルメディア</div>
      <div :class="$style.description2">
        概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト
      </div>
      <div :class="$style.div3">対応ファネル</div>
      <div :class="$style.divider5" />
      <div :class="$style.div4">閲覧/視聴/読者ターゲット</div>
      <div :class="$style.description3">女性 , 社会人</div>
      <div :class="$style.chips1InputbTextOnlyA9">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar25.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">興味</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA10">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar26.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">認知</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA11">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar27.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">理解</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA12">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar28.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">購買 / 来店促進</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA13">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar29.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">推奨</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA14">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar30.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">リピート</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.dividerParent">
        <div :class="$style.divider6" />
        <div :class="$style.imageGroup">
          <img :class="$style.imageIcon" alt="" src="/image1@2x.png" />
          <b :class="$style.title1"
            >記事タイトル記事タイトル記事タイトル記事タイトル記事タイトル記事タイトル記事タイトル記事タイトル</b
          >
          <div :class="$style.div5">公開日 : 2022/12/20</div>
        </div>
      </div>
      <div :class="$style.div6">主なユーザー属性</div>
      <div :class="$style.groupParent">
        <div :class="$style.rectangleParent">
          <div :class="$style.groupChild7" />
          <div :class="$style.groupChild8" />
          <div :class="$style.groupChild9" />
          <div :class="$style.groupChild10" />
        </div>
        <div :class="$style.descriptionParent">
          <div :class="$style.description4">20代 男性 : 00%</div>
          <div :class="$style.groupChild11" />
        </div>
        <div :class="$style.descriptionGroup">
          <div :class="$style.description4">30代 女性 : 00%</div>
          <div :class="$style.groupChild12" />
        </div>
        <div :class="$style.descriptionContainer">
          <div :class="$style.description6">その他 : 00%</div>
          <div :class="$style.groupChild13" />
        </div>
        <div :class="$style.groupDiv">
          <div :class="$style.description4">30代 男性 : 00%</div>
          <div :class="$style.groupChild14" />
        </div>
      </div>
      <div :class="$style.groupContainer">
        <div :class="$style.rectangleGroup">
          <div :class="$style.groupChild15" />
          <div :class="$style.groupChild16" />
        </div>
        <div :class="$style.descriptionParent1">
          <div :class="$style.description8">女性 : 00%</div>
          <div :class="$style.groupChild17" />
        </div>
        <div :class="$style.descriptionParent2">
          <div :class="$style.description8">男性 : 00%</div>
          <div :class="$style.groupChild18" />
        </div>
      </div>
      <div :class="$style.rectangleContainer">
        <div :class="$style.groupChild19" />
        <div :class="$style.div7">シーズン限定メニュー</div>
        <div :class="$style.description10">直前割引情報があります！</div>
        <img :class="$style.localOfferIcon" alt="" src="/local-offer1.svg" />
      </div>
    </div>
    <div :class="$style.bgContainer">
      <div :class="$style.bg4" />
      <div :class="$style.unstyledbutton10">
        <img :class="$style.icon18" alt="" src="/icon8.svg" />
        <div :class="$style.button">お気に入り</div>
        <div :class="$style.unstyledbuttonChild" />
        <div :class="$style.button">10</div>
      </div>
      <div :class="$style.buttonoutlined9">
        <div :class="$style.unstyledbutton">
          <div :class="$style.button">お問い合わせ</div>
        </div>
      </div>
      <div :class="$style.bg3" />
      <div :class="$style.content7">
        <img :class="$style.maskedIcon1" alt="" src="/masked-icon10.svg" />
        <img :class="$style.icon18" alt="" src="/icon9.svg" />
        <div :class="$style.button10">比較</div>
      </div>
      <b :class="$style.title2">MediaTitleMediaTitle</b>
      <div :class="$style.imageContainer">
        <div :class="$style.image" />
        <img :class="$style.image2Icon" alt="" src="/image-2@2x.png" />
      </div>
      <div :class="$style.choiceChipbActiveContainer">
        <div :class="$style.choiceChipbActive">
          <div :class="$style.avatar">
            <img :class="$style.maskedIcon" alt="" src="/avatar31.svg" />
          </div>
          <div :class="$style.label1">
            <div :class="$style.label2">ライフスタイル</div>
          </div>
          <div :class="$style.icon">
            <img :class="$style.icon1" alt="" src="/-icon.svg" />
          </div>
        </div>
      </div>
      <div :class="$style.description11">
        <p :class="$style.p">1.食品・飲料 00%</p>
        <p :class="$style.p">2.家庭用品・トイレタリー 00%</p>
        <p :class="$style.p">3.化粧品 00%</p>
      </div>
      <div :class="$style.top31">広告主の業種/商材Top3</div>
      <div :class="$style.divider7" />
      <div :class="$style.divider8" />
      <div :class="$style.divider9" />
      <div :class="$style.divider10" />
      <div :class="$style.divider11" />
      <div :class="$style.div9">メディア概要</div>
      <div :class="$style.div10">メディア種別</div>
      <div :class="$style.description12">ポータルメディア</div>
      <div :class="$style.description13">
        概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト概要テキスト
      </div>
      <div :class="$style.div11">対応ファネル</div>
      <div :class="$style.divider12" />
      <div :class="$style.div12">閲覧/視聴/読者ターゲット</div>
      <div :class="$style.description14">女性 , 社会人</div>
      <div :class="$style.chips1InputbTextOnlyA15">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar32.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">興味</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA16">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar33.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">認知</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA17">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar34.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">理解</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA18">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar35.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">購買 / 来店促進</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA19">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar36.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">推奨</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.chips1InputbTextOnlyA20">
        <div :class="$style.avatar">
          <img :class="$style.maskedIcon" alt="" src="/avatar37.svg" />
        </div>
        <div :class="$style.label1">
          <div :class="$style.label2">リピート</div>
        </div>
        <div :class="$style.icon">
          <img :class="$style.icon1" alt="" src="/-icon1.svg" />
        </div>
      </div>
      <div :class="$style.div13">主なユーザー属性</div>
      <div :class="$style.groupParent1">
        <div :class="$style.rectangleParent">
          <div :class="$style.groupChild7" />
          <div :class="$style.groupChild8" />
          <div :class="$style.groupChild9" />
          <div :class="$style.groupChild10" />
        </div>
        <div :class="$style.descriptionParent">
          <div :class="$style.description4">20代 男性 : 00%</div>
          <div :class="$style.groupChild11" />
        </div>
        <div :class="$style.descriptionGroup">
          <div :class="$style.description4">30代 女性 : 00%</div>
          <div :class="$style.groupChild12" />
        </div>
        <div :class="$style.descriptionContainer">
          <div :class="$style.description6">その他 : 00%</div>
          <div :class="$style.groupChild13" />
        </div>
        <div :class="$style.groupDiv">
          <div :class="$style.description4">30代 男性 : 00%</div>
          <div :class="$style.groupChild14" />
        </div>
      </div>
      <div :class="$style.groupParent2">
        <div :class="$style.rectangleGroup">
          <div :class="$style.groupChild15" />
          <div :class="$style.groupChild16" />
        </div>
        <div :class="$style.descriptionParent1">
          <div :class="$style.description8">女性 : 00%</div>
          <div :class="$style.groupChild17" />
        </div>
        <div :class="$style.descriptionParent2">
          <div :class="$style.description8">男性 : 00%</div>
          <div :class="$style.groupChild18" />
        </div>
      </div>
    </div>
    <div :class="$style.div14">
      <div :class="$style.navigationItem">
        <div :class="$style.div15">登録情報</div>
        <img :class="$style.icon50" alt="" src="/icon10.svg" />
      </div>
      <div :class="$style.navigationItem1">
        <div :class="$style.div15">商談管理</div>
        <img :class="$style.icon50" alt="" src="/icon10.svg" />
      </div>
      <div :class="$style.navigationItem2">
        <div :class="$style.div15">与件一覧</div>
        <img :class="$style.icon50" alt="" src="/icon10.svg" />
      </div>
      <div :class="$style.navigationItem3">
        <div :class="$style.div15">担当者一覧</div>
        <img :class="$style.icon50" alt="" src="/icon10.svg" />
      </div>
      <div :class="$style.navigationItem4">
        <div :class="$style.div15">ホーム</div>
        <img :class="$style.icon50" alt="" src="/icon10.svg" />
      </div>
      <div :class="$style.navigationItem5">
        <div :class="$style.div15">お気に入りメディア</div>
        <img :class="$style.icon50" alt="" src="/icon10.svg" />
      </div>
      <div :class="$style.navigationItem6">
        <div :class="$style.rectangle" />
        <img :class="$style.icon50" alt="" src="/icon10.svg" />
        <img :class="$style.vectorIcon" alt="" src="/vector1.svg" />
        <b :class="$style.b9">メディア一覧</b>
      </div>
      <div :class="$style.navigationItem7">
        <div :class="$style.div15">お知らせ</div>
        <img :class="$style.icon50" alt="" src="/icon10.svg" />
      </div>
      <div :class="$style.navigationItem8">
        <img :class="$style.vectorIcon" alt="" src="/1logout.svg" />
        <div :class="$style.div15">ログアウト</div>
        <img :class="$style.icon59" alt="" src="/icon10.svg" />
      </div>
      <div :class="$style.koukokunushiParent">
        <div :class="$style.koukokunushi">株式会社KOUKOKUNUSHI</div>
        <div :class="$style.ellipseParent">
          <div :class="$style.ellipseDiv" />
          <img :class="$style.image1Icon" alt="" src="/image-14@2x.png" />
        </div>
      </div>
      <div :class="$style.child" />
      <div :class="$style.div23">広告主</div>
      <img :class="$style.image1Icon1" alt="" src="/image-12@2x.png" />
      <img :class="$style.icon60" alt="" src="/1account-circle.svg" />
      <img :class="$style.icon61" alt="" src="/icon3.svg" />
      <img :class="$style.icon62" alt="" src="/icon4.svg" />
      <img :class="$style.icon63" alt="" src="/icon11.svg" />
      <img :class="$style.icon64" alt="" src="/icon5.svg" />
      <img :class="$style.icon65" alt="" src="/icon12.svg" />
      <img :class="$style.icon66" alt="" src="/icon13.svg" />
      <img :class="$style.icon67" alt="" src="/1notice.svg" />
    </div>
    <div :class="$style.heading">
      <div :class="$style.bg6" />
      <b :class="$style.b10">メディア一覧</b>
    </div>
  </div>
</template>
<script lang="ts">
  import { defineComponent, ref } from "vue";

  export default defineComponent({
    name: "K101",
  });
</script>
<style module>
  .button {
    position: relative;
    letter-spacing: 0.4px;
    line-height: 24px;
    text-transform: uppercase;
    font-weight: 500;
  }
  .maskedIcon {
    position: relative;
    width: 20px;
    height: 20px;
  }
  .content {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: var(--gap-5xs);
  }
  .unstyledbutton {
    overflow: hidden;
    display: flex;
    flex-direction: column;
    padding: var(--padding-7xs) var(--padding-base);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .buttonoutlined {
    position: absolute;
    height: 1.74%;
    top: 36.1%;
    bottom: 62.16%;
    left: calc(44.5% - 440px);
    border-radius: var(--br-9xs);
    background-color: var(--black);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: var(--white);
  }
  .bg {
    position: absolute;
    top: -1px;
    left: -1px;
    border-radius: var(--br-9xs);
    background-color: var(--white);
    border: 1px solid var(--lightgray);
    box-sizing: border-box;
    width: 1138px;
    height: 622px;
  }
  .bg1 {
    position: absolute;
    top: 24px;
    left: 23px;
    border-radius: var(--br-9xs) 0px 0px var(--br-9xs);
    background-color: var(--color-whitesmoke-100);
    width: 195px;
    height: 512px;
  }
  .b {
    position: absolute;
    top: 496px;
    left: 47px;
    letter-spacing: 0.1px;
    line-height: 20px;
  }
  .label {
    flex: 1;
    position: relative;
    letter-spacing: 0.15px;
    line-height: 24px;
  }
  .container {
    align-self: stretch;
    flex: 1;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    padding: var(--padding-5xs) 0px var(--padding-6xs);
    align-items: center;
    justify-content: flex-start;
  }
  .input {
    align-self: stretch;
    flex: 1;
    border-radius: var(--br-9xs);
    background-color: var(--white);
    border: 1px solid var(--gray);
    display: flex;
    flex-direction: column;
    padding: 0px var(--padding-xs);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .textFieldoutlined {
    position: absolute;
    top: 0px;
    left: 0px;
    width: 336px;
    height: 36px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .textFieldoutlinedWrapper {
    position: absolute;
    top: 488px;
    left: 242px;
    width: 336px;
    height: 36px;
    font-size: var(--material-theme-title-medium-size);
    color: var(--gray);
  }
  .b1 {
    position: absolute;
    top: 98px;
    left: 47px;
    letter-spacing: 0.1px;
    line-height: 20px;
  }
  .b2 {
    position: absolute;
    top: 154px;
    left: 47px;
    letter-spacing: 0.1px;
    line-height: 20px;
  }
  .b3 {
    position: absolute;
    top: 205px;
    left: 47px;
    letter-spacing: 0.1px;
    line-height: 20px;
  }
  .b4 {
    position: absolute;
    top: 266px;
    left: 47px;
    letter-spacing: 0.1px;
    line-height: 20px;
  }
  .b5 {
    position: absolute;
    top: 322px;
    left: 47px;
    letter-spacing: 0.1px;
    line-height: 20px;
  }
  .unstyledbutton1 {
    overflow: hidden;
    display: flex;
    flex-direction: column;
    padding: var(--padding-9xs) var(--padding-5xs);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .buttonoutlined1 {
    position: absolute;
    height: 5.16%;
    top: 32.9%;
    bottom: 61.94%;
    left: calc(50% - 326px);
    border-radius: var(--br-9xs);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: var(--blue);
  }
  .buttonoutlined2 {
    position: absolute;
    height: 5.16%;
    top: 14.84%;
    bottom: 80%;
    left: calc(50% - 326px);
    border-radius: var(--br-9xs);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: var(--blue);
  }
  .b6 {
    position: absolute;
    top: 378px;
    left: 47px;
    letter-spacing: 0.1px;
    line-height: 20px;
  }
  .buttonoutlined3 {
    position: absolute;
    height: 5.16%;
    top: 60%;
    bottom: 34.84%;
    left: calc(50% - 326px);
    border-radius: var(--br-9xs);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: var(--blue);
  }
  .buttonoutlined4 {
    position: absolute;
    height: 5.16%;
    top: 50.97%;
    bottom: 43.87%;
    left: calc(50% - 326px);
    border-radius: var(--br-9xs);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: var(--blue);
  }
  .b7 {
    position: absolute;
    top: 436px;
    left: 47px;
    letter-spacing: 0.1px;
    line-height: 20px;
  }
  .avatar {
    width: 24px;
    height: 24px;
    display: none;
    flex-direction: row;
    align-items: center;
    justify-content: center;
  }
  .label2 {
    position: relative;
    /* letter-spacing: 0.25px; */
    line-height: 20px;
  }
  .label1 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    padding: 0px var(--padding-5xs);
    align-items: center;
    justify-content: center;
  }
  .icon1 {
    position: relative;
    width: 18px;
    height: 18px;
  }
  .icon {
    align-self: stretch;
    width: 21px;
    display: none;
    flex-direction: row;
    padding: 0px var(--padding-9xs) 0px 0px;
    box-sizing: border-box;
    align-items: center;
    justify-content: center;
  }
  .chips1InputbTextOnlyA {
    position: absolute;
    top: calc(50% - 50px);
    left: 297px;
    border-radius: var(--br-base);
    border: 1px solid var(--gray);
    box-sizing: border-box;
    height: 32px;
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .chips1InputbTextOnlyA1 {
    position: absolute;
    top: calc(50% - 50px);
    left: 242px;
    border-radius: var(--br-base);
    border: 1px solid var(--gray);
    box-sizing: border-box;
    height: 32px;
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .chips1InputbTextOnlyA2 {
    position: absolute;
    top: calc(50% - 50px);
    left: 351px;
    border-radius: var(--br-base);
    border: 1px solid var(--gray);
    box-sizing: border-box;
    height: 32px;
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .arrowdropdownfilledIcon {
    position: absolute;
    top: 8px;
    left: 304px;
    width: 20px;
    height: 20px;
    overflow: hidden;
  }
  .textFieldoutlinedParent {
    position: absolute;
    top: 428px;
    left: 242px;
    width: 336px;
    height: 36px;
    font-size: var(--material-theme-title-medium-size);
    color: var(--gray);
  }
  .groupChild {
    position: absolute;
    top: 248px;
    left: 23px;
    border-bottom: 1px solid var(--lightgray);
    box-sizing: border-box;
    width: 1088px;
    height: 56px;
  }
  .b8 {
    position: absolute;
    top: 42px;
    left: 47px;
    letter-spacing: 0.1px;
    line-height: 20px;
  }
  .groupItem {
    position: absolute;
    top: 24px;
    left: 23px;
    border-radius: 0px var(--br-9xs) 0px 0px;
    border-bottom: 1px solid var(--lightgray);
    box-sizing: border-box;
    width: 1088px;
    height: 56px;
  }
  .groupInner {
    position: absolute;
    top: 80px;
    left: 23px;
    border-bottom: 1px solid var(--lightgray);
    box-sizing: border-box;
    width: 1088px;
    height: 56px;
  }
  .rectangleDiv {
    position: absolute;
    top: 192px;
    left: 23px;
    border-bottom: 1px solid var(--lightgray);
    box-sizing: border-box;
    width: 1088px;
    height: 56px;
  }
  .groupChild1 {
    position: absolute;
    top: 304px;
    left: 23px;
    border-bottom: 1px solid var(--lightgray);
    box-sizing: border-box;
    width: 1088px;
    height: 56px;
  }
  .groupChild2 {
    position: absolute;
    top: 360px;
    left: 23px;
    border-bottom: 1px solid var(--lightgray);
    box-sizing: border-box;
    width: 1088px;
    height: 56px;
  }
  .groupChild3 {
    position: absolute;
    top: 416px;
    left: 23px;
    border-right: 1px solid var(--lightgray);
    border-bottom: 1px solid var(--lightgray);
    box-sizing: border-box;
    width: 1088px;
    height: 60px;
  }
  .groupChild4 {
    position: absolute;
    top: 405px;
    left: 23px;
    width: 1088px;
    height: 60px;
  }
  .buttonoutlined5 {
    position: absolute;
    height: 5.16%;
    top: 5.81%;
    bottom: 89.03%;
    left: calc(50% - 326px);
    border-radius: var(--br-9xs);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: var(--blue);
  }
  .groupChild5 {
    position: absolute;
    top: 136px;
    left: 23px;
    border-bottom: 1px solid var(--lightgray);
    box-sizing: border-box;
    width: 1088px;
    height: 56px;
  }
  .chips1InputbTextOnlyA3 {
    position: absolute;
    top: calc(50% - 162px);
    left: 303px;
    border-radius: var(--br-base);
    border: 1px solid var(--gray);
    box-sizing: border-box;
    height: 32px;
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .chips1InputbTextOnlyA4 {
    position: absolute;
    top: calc(50% - 162px);
    left: 242px;
    border-radius: var(--br-base);
    border: 1px solid var(--gray);
    box-sizing: border-box;
    height: 32px;
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .chips1InputbTextOnlyA5 {
    position: absolute;
    top: calc(50% - 162px);
    left: 364px;
    border-radius: var(--br-base);
    border: 1px solid var(--gray);
    box-sizing: border-box;
    height: 32px;
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .chips1InputbTextOnlyA6 {
    position: absolute;
    top: calc(50% - 162px);
    left: 425px;
    border-radius: var(--br-base);
    border: 1px solid var(--gray);
    box-sizing: border-box;
    height: 32px;
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .chips1InputbTextOnlyA7 {
    position: absolute;
    top: calc(50% - 162px);
    left: 645px;
    border-radius: var(--br-base);
    border: 1px solid var(--gray);
    box-sizing: border-box;
    height: 32px;
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .chips1InputbTextOnlyA8 {
    position: absolute;
    top: calc(50% - 162px);
    left: 556px;
    border-radius: var(--br-base);
    border: 1px solid var(--gray);
    box-sizing: border-box;
    height: 32px;
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .groupChild6 {
    position: absolute;
    top: 24px;
    left: 23px;
    border-radius: var(--br-9xs);
    border: 1px solid var(--lightgray);
    box-sizing: border-box;
    width: 1088px;
    height: 512px;
  }
  .buttonoutlined6 {
    position: absolute;
    height: 5.81%;
    top: 90.32%;
    bottom: 3.87%;
    left: calc(50% + 127px);
    border-radius: var(--br-9xs);
    border: 1px solid var(--darkgray);
    box-sizing: border-box;
    width: 200px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .buttonoutlined7 {
    position: absolute;
    height: 5.81%;
    top: 90.32%;
    bottom: 3.87%;
    left: calc(50% + 343px);
    border-radius: var(--br-9xs);
    background-color: var(--blue);
    border: 1px solid var(--blue);
    box-sizing: border-box;
    width: 200px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: var(--white);
  }
  .bgParent {
    position: absolute;
    top: 104px;
    left: 281px;
    width: 1136px;
    height: 620px;
  }
  .bg2 {
    position: absolute;
    height: 100.28%;
    width: 100.18%;
    top: -0.14%;
    right: -0.09%;
    bottom: -0.14%;
    left: -0.09%;
    border-radius: var(--br-9xs);
    background-color: var(--white);
    border: 1px solid var(--lightgray);
    box-sizing: border-box;
  }
  .icon18 {
    position: relative;
    width: 24px;
    height: 24px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .unstyledbuttonChild {
    position: relative;
    background-color: var(--lightgray);
    width: 1px;
    height: 20px;
  }
  .unstyledbutton8 {
    position: absolute;
    top: calc(50% + 287.5px);
    left: calc(50% + 142px);
    border-radius: var(--br-9xs);
    background-color: var(--color-whitesmoke-100);
    overflow: hidden;
    display: flex;
    flex-direction: row;
    padding: var(--padding-7xs) var(--padding-5xl) var(--padding-7xs)
      var(--padding-base);
    align-items: center;
    justify-content: center;
    gap: var(--gap-5xs);
  }
  .buttonoutlined8 {
    position: absolute;
    width: 17.61%;
    top: calc(50% + 287.5px);
    right: 2.82%;
    left: 79.58%;
    border-radius: var(--br-9xs);
    background-color: var(--red);
    border: 1px solid var(--red);
    box-sizing: border-box;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: var(--white);
  }
  .bg3 {
    position: absolute;
    height: 100%;
    width: 4.23%;
    top: 0%;
    right: 95.77%;
    bottom: 0%;
    left: 0%;
    border-radius: var(--br-9xs) 0px 0px var(--br-9xs);
    background-color: var(--lightgray);
  }
  .maskedIcon1 {
    position: relative;
    width: 16px;
    height: 20px;
    display: none;
  }
  .button10 {
    position: relative;
    line-height: 24px;
    text-transform: uppercase;
    font-weight: 500;
  }
  .content6 {
    position: absolute;
    top: 331px;
    left: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: var(--gap-11xs);
  }
  .title {
    position: absolute;
    width: 65.05%;
    top: 9.56%;
    left: 32.39%;
    font-size: var(--font-size-lg);
    line-height: 140%;
    display: inline-block;
  }
  .image {
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0%;
    right: 0%;
    bottom: 0%;
    left: 0%;
    border-radius: var(--br-9xs);
    background-color: var(--background);
  }
  .image2Icon {
    position: absolute;
    height: 40%;
    width: 88.28%;
    top: 30.01%;
    right: 5.46%;
    bottom: 29.99%;
    left: 6.25%;
    border-radius: var(--br-9xs);
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
    object-fit: cover;
  }
  .imageParent {
    position: absolute;
    height: 19.69%;
    width: 22.54%;
    top: 4.5%;
    right: 70.42%;
    bottom: 75.81%;
    left: 7.04%;
  }
  .choiceChipbActive {
    position: absolute;
    top: calc(50% - 12px);
    left: 0px;
    border-radius: var(--br-9xs);
    background-color: var(--color-steelblue-100);
    border: 1px solid var(--blue);
    box-sizing: border-box;
    height: 24px;
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .choiceChipbActiveWrapper {
    position: absolute;
    top: calc(50% - 323.5px);
    left: 415px;
    width: 110px;
    height: 24px;
    font-size: var(--material-theme-body-small-size);
    color: var(--blue);
  }
  .p {
    margin: 0;
  }
  .description {
    position: absolute;
    width: 23.06%;
    top: 33.76%;
    left: 52.02%;
    letter-spacing: 0.25px;
    line-height: 20px;
    display: none;
  }
  .top3 {
    position: absolute;
    top: 36.57%;
    left: 33.45%;
    letter-spacing: 0.1px;
    line-height: 20px;
    font-weight: 500;
  }
  .divider {
    position: absolute;
    height: 0.14%;
    width: 64.79%;
    top: 24.47%;
    right: 2.82%;
    bottom: 75.39%;
    left: 32.39%;
    background-color: var(--lightgray);
  }
  .divider1 {
    position: absolute;
    height: 0.14%;
    width: 64.79%;
    top: 43.88%;
    right: 2.82%;
    bottom: 55.98%;
    left: 32.39%;
    background-color: var(--lightgray);
  }
  .divider2 {
    position: absolute;
    height: 0.14%;
    width: 64.79%;
    top: 50.21%;
    right: 2.82%;
    bottom: 49.65%;
    left: 32.39%;
    background-color: var(--lightgray);
  }
  .divider3 {
    position: absolute;
    height: 0.14%;
    width: 64.79%;
    top: 31.93%;
    right: 2.82%;
    bottom: 67.93%;
    left: 32.39%;
    background-color: var(--lightgray);
  }
  .divider4 {
    position: absolute;
    height: 0.14%;
    width: 64.79%;
    top: 56.54%;
    right: 2.82%;
    bottom: 43.32%;
    left: 32.39%;
    background-color: var(--lightgray);
  }
  .div1 {
    position: absolute;
    top: 18.57%;
    left: 33.45%;
    letter-spacing: 0.1px;
    line-height: 20px;
    font-weight: 500;
  }
  .div2 {
    position: absolute;
    top: 45.71%;
    left: 33.45%;
    letter-spacing: 0.1px;
    line-height: 20px;
    font-weight: 500;
  }
  .description1 {
    position: absolute;
    top: 45.71%;
    left: 52.02%;
    line-height: 140%;
  }
  .description2 {
    position: absolute;
    height: 5.63%;
    width: 44.1%;
    top: 17.16%;
    left: 52.02%;
    letter-spacing: 0.25px;
    line-height: 20px;
    display: inline-block;
  }
  .div3 {
    position: absolute;
    top: 26.86%;
    left: 33.45%;
    letter-spacing: 0.1px;
    line-height: 20px;
    font-weight: 500;
  }
  .divider5 {
    position: absolute;
    height: 0.14%;
    width: 64.79%;
    top: 15.33%;
    right: 2.82%;
    bottom: 84.53%;
    left: 32.39%;
    background-color: var(--lightgray);
  }
  .div4 {
    position: absolute;
    top: 52.04%;
    left: 33.45%;
    letter-spacing: 0.46px;
    line-height: 20px;
    text-transform: uppercase;
    font-weight: 500;
  }
  .description3 {
    position: absolute;
    top: 52.04%;
    left: 52.02%;
    line-height: 140%;
  }
  .chips1InputbTextOnlyA9 {
    position: absolute;
    top: calc(50% - 168.5px);
    left: 648px;
    border-radius: var(--br-base);
    background-color: var(--color-whitesmoke-100);
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--material-theme-body-small-size);
    color: var(--darkgray);
  }
  .chips1InputbTextOnlyA10 {
    position: absolute;
    top: calc(50% - 168.5px);
    left: 591px;
    border-radius: var(--br-base);
    background-color: var(--black);
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--material-theme-body-small-size);
    color: var(--white);
  }
  .chips1InputbTextOnlyA11 {
    position: absolute;
    top: calc(50% - 168.5px);
    left: 705px;
    border-radius: var(--br-base);
    background-color: var(--color-whitesmoke-100);
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--material-theme-body-small-size);
    color: var(--darkgray);
  }
  .chips1InputbTextOnlyA12 {
    position: absolute;
    top: calc(50% - 168.5px);
    left: 762px;
    border-radius: var(--br-base);
    background-color: var(--black);
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--material-theme-body-small-size);
    color: var(--white);
  }
  .chips1InputbTextOnlyA13 {
    position: absolute;
    top: calc(50% - 168.5px);
    left: 960px;
    border-radius: var(--br-base);
    background-color: var(--color-whitesmoke-100);
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--material-theme-body-small-size);
    color: var(--darkgray);
  }
  .chips1InputbTextOnlyA14 {
    position: absolute;
    top: calc(50% - 168.5px);
    left: 879px;
    border-radius: var(--br-base);
    background-color: var(--color-whitesmoke-100);
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--material-theme-body-small-size);
    color: var(--darkgray);
  }
  .divider6 {
    position: absolute;
    height: 100.71%;
    width: 100.1%;
    top: -0.36%;
    right: -0.05%;
    bottom: -0.36%;
    left: -0.05%;
    border-radius: var(--br-11xs);
    background-color: var(--color-whitesmoke-100);
    border: 1px solid var(--lightgray);
    box-sizing: border-box;
  }
  .imageIcon {
    position: absolute;
    height: 100%;
    width: 30.04%;
    top: 0%;
    right: 69.96%;
    bottom: 0%;
    left: 0%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
    object-fit: cover;
  }
  .title1 {
    position: absolute;
    top: 25%;
    left: 31.65%;
    letter-spacing: 0.15px;
    line-height: 140%;
    display: inline-block;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    width: 678px;
    height: 43px;
  }
  .div5 {
    position: absolute;
    top: 0%;
    left: 31.65%;
    font-size: var(--medium-14-size);
    letter-spacing: 0.25px;
    line-height: 20px;
    color: var(--bluegray);
  }
  .imageGroup {
    position: absolute;
    height: 80%;
    width: 96.88%;
    top: 8.57%;
    right: 1.56%;
    bottom: 11.43%;
    left: 1.56%;
  }
  .dividerParent {
    position: absolute;
    height: 19.69%;
    width: 90.14%;
    top: 67.37%;
    right: 2.82%;
    bottom: 12.94%;
    left: 7.04%;
    font-size: var(--material-theme-title-medium-size);
  }
  .div6 {
    position: absolute;
    top: 26.44%;
    left: 7.04%;
    letter-spacing: 0.4px;
    line-height: 20px;
    font-weight: 500;
  }
  .groupChild7 {
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0%;
    right: 0%;
    bottom: 0%;
    left: 0%;
    background-color: var(--color-lightgray);
  }
  .groupChild8 {
    position: absolute;
    height: 100%;
    width: 70.47%;
    top: 0%;
    right: 29.53%;
    bottom: 0%;
    left: 0%;
    background-color: var(--color-royalblue-100);
  }
  .groupChild9 {
    position: absolute;
    height: 100%;
    width: 32.28%;
    top: 0%;
    right: 39.76%;
    bottom: 0%;
    left: 27.95%;
    background-color: var(--color-royalblue-300);
  }
  .groupChild10 {
    position: absolute;
    height: 100%;
    width: 43.7%;
    top: 0%;
    right: 56.3%;
    bottom: 0%;
    left: 0%;
    background-color: var(--color-midnightblue);
  }
  .rectangleParent {
    position: absolute;
    height: 15.38%;
    width: 100%;
    top: 0%;
    right: 0%;
    bottom: 84.62%;
    left: 0%;
  }
  .description4 {
    position: absolute;
    top: 0%;
    left: 16.82%;
    letter-spacing: 0.4px;
    line-height: 16px;
  }
  .groupChild11 {
    position: absolute;
    height: 62.5%;
    width: 9.35%;
    top: 18.75%;
    right: 90.65%;
    bottom: 18.75%;
    left: 0%;
    background-color: var(--color-royalblue-300);
  }
  .descriptionParent {
    position: absolute;
    height: 30.77%;
    width: 41.8%;
    top: 30.77%;
    right: 10.16%;
    bottom: 38.46%;
    left: 48.05%;
  }
  .groupChild12 {
    position: absolute;
    height: 62.5%;
    width: 9.35%;
    top: 18.75%;
    right: 90.65%;
    bottom: 18.75%;
    left: 0%;
    background-color: var(--color-royalblue-100);
  }
  .descriptionGroup {
    position: absolute;
    height: 30.77%;
    width: 41.8%;
    top: 69.23%;
    right: 58.2%;
    bottom: 0%;
    left: 0%;
  }
  .description6 {
    position: absolute;
    top: 0%;
    left: 20.22%;
    letter-spacing: 0.4px;
    line-height: 16px;
  }
  .groupChild13 {
    position: absolute;
    height: 62.5%;
    width: 11.24%;
    top: 18.75%;
    right: 88.76%;
    bottom: 18.75%;
    left: 0%;
    background-color: var(--color-lightgray);
  }
  .descriptionContainer {
    position: absolute;
    height: 30.77%;
    width: 34.77%;
    top: 69.23%;
    right: 17.19%;
    bottom: 0%;
    left: 48.05%;
  }
  .groupChild14 {
    position: absolute;
    height: 62.5%;
    width: 9.35%;
    top: 18.75%;
    right: 90.65%;
    bottom: 18.75%;
    left: 0%;
    background-color: var(--color-midnightblue);
  }
  .groupDiv {
    position: absolute;
    height: 30.77%;
    width: 41.8%;
    top: 30.77%;
    right: 58.2%;
    bottom: 38.46%;
    left: 0%;
  }
  .groupParent {
    position: absolute;
    height: 7.31%;
    width: 22.54%;
    top: 39.38%;
    right: 70.42%;
    bottom: 53.31%;
    left: 7.04%;
    font-size: var(--material-theme-body-small-size);
  }
  .groupChild15 {
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0%;
    right: 0%;
    bottom: 0%;
    left: 0%;
    background-color: var(--color-mediumpurple);
  }
  .groupChild16 {
    position: absolute;
    height: 100%;
    width: 43.7%;
    top: 0%;
    right: 56.3%;
    bottom: 0%;
    left: 0%;
    background-color: var(--color-blueviolet);
  }
  .rectangleGroup {
    position: absolute;
    height: 25%;
    width: 100%;
    top: 0%;
    right: 0%;
    bottom: 75%;
    left: 0%;
  }
  .description8 {
    position: absolute;
    top: 0%;
    left: 23.68%;
    letter-spacing: 0.4px;
    line-height: 16px;
  }
  .groupChild17 {
    position: absolute;
    height: 62.5%;
    width: 13.16%;
    top: 18.75%;
    right: 86.84%;
    bottom: 18.75%;
    left: 0%;
    background-color: var(--color-mediumpurple);
  }
  .descriptionParent1 {
    position: absolute;
    height: 50%;
    width: 29.69%;
    top: 50%;
    right: 34.38%;
    bottom: 0%;
    left: 35.94%;
  }
  .groupChild18 {
    position: absolute;
    height: 62.5%;
    width: 13.16%;
    top: 18.75%;
    right: 86.84%;
    bottom: 18.75%;
    left: 0%;
    background-color: var(--color-blueviolet);
  }
  .descriptionParent2 {
    position: absolute;
    height: 50%;
    width: 29.69%;
    top: 50%;
    right: 70.31%;
    bottom: 0%;
    left: 0%;
  }
  .groupContainer {
    position: absolute;
    height: 4.5%;
    width: 22.54%;
    top: 31.5%;
    right: 70.42%;
    bottom: 63.99%;
    left: 7.04%;
    font-size: var(--material-theme-body-small-size);
  }
  .groupChild19 {
    position: absolute;
    top: 0px;
    left: 0px;
    border-radius: var(--br-11xs);
    background-color: var(--lightred);
    width: 736px;
    height: 44px;
  }
  .div7 {
    position: absolute;
    width: 19.65%;
    top: 27.27%;
    left: 4.91%;
    letter-spacing: 0.46px;
    line-height: 20px;
    text-transform: uppercase;
    font-weight: 500;
    display: inline-block;
  }
  .description10 {
    position: absolute;
    width: 22.92%;
    top: 27.27%;
    left: 30.42%;
    line-height: 20px;
    font-weight: 500;
    display: inline-block;
  }
  .localOfferIcon {
    position: absolute;
    top: 12px;
    left: 12.05px;
    width: 20.08px;
    height: 20px;
    overflow: hidden;
  }
  .rectangleContainer {
    position: absolute;
    top: 419px;
    left: 368px;
    width: 736px;
    height: 44px;
    color: var(--red);
  }
  .bgGroup {
    position: absolute;
    height: 34.31%;
    width: 78.89%;
    top: 39%;
    right: 1.67%;
    bottom: 26.69%;
    left: 17.44%;
  }
  .bg4 {
    position: absolute;
    height: 100.4%;
    width: 100.18%;
    top: -0.2%;
    right: -0.09%;
    bottom: -0.2%;
    left: -0.09%;
    border-radius: var(--br-9xs);
    background-color: var(--white);
    border: 1px solid var(--lightgray);
    box-sizing: border-box;
  }
  .unstyledbutton10 {
    position: absolute;
    top: calc(50% + 179.5px);
    left: calc(50% + 142px);
    border-radius: var(--br-9xs);
    background-color: var(--color-whitesmoke-100);
    overflow: hidden;
    display: flex;
    flex-direction: row;
    padding: var(--padding-7xs) var(--padding-5xl) var(--padding-7xs)
      var(--padding-base);
    align-items: center;
    justify-content: center;
    gap: var(--gap-5xs);
  }
  .buttonoutlined9 {
    position: absolute;
    width: 17.61%;
    top: calc(50% + 179.5px);
    right: 2.82%;
    left: 79.58%;
    border-radius: var(--br-9xs);
    background-color: var(--red);
    border: 1px solid var(--red);
    box-sizing: border-box;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: var(--white);
  }
  .content7 {
    position: absolute;
    top: 223px;
    left: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: var(--gap-11xs);
  }
  .title2 {
    position: absolute;
    width: 65.05%;
    top: 13.74%;
    left: 32.39%;
    font-size: var(--font-size-lg);
    line-height: 140%;
    display: inline-block;
  }
  .imageContainer {
    position: absolute;
    height: 28.28%;
    width: 22.54%;
    top: 6.46%;
    right: 70.42%;
    bottom: 65.25%;
    left: 7.04%;
  }
  .choiceChipbActiveContainer {
    position: absolute;
    top: calc(50% - 215.5px);
    left: 415px;
    width: 110px;
    height: 24px;
    font-size: var(--material-theme-body-small-size);
    color: var(--blue);
  }
  .description11 {
    position: absolute;
    width: 23.06%;
    top: 48.48%;
    left: 52.02%;
    letter-spacing: 0.25px;
    line-height: 20px;
    display: inline-block;
  }
  .top31 {
    position: absolute;
    top: 52.53%;
    left: 33.45%;
    letter-spacing: 0.1px;
    line-height: 20px;
    font-weight: 500;
  }
  .divider7 {
    position: absolute;
    height: 0.2%;
    width: 64.79%;
    top: 35.15%;
    right: 2.82%;
    bottom: 64.65%;
    left: 32.39%;
    background-color: var(--lightgray);
  }
  .divider8 {
    position: absolute;
    height: 0.2%;
    width: 64.79%;
    top: 63.03%;
    right: 2.82%;
    bottom: 36.77%;
    left: 32.39%;
    background-color: var(--lightgray);
  }
  .divider9 {
    position: absolute;
    height: 0.2%;
    width: 64.79%;
    top: 72.12%;
    right: 2.82%;
    bottom: 27.68%;
    left: 32.39%;
    background-color: var(--lightgray);
  }
  .divider10 {
    position: absolute;
    height: 0.2%;
    width: 64.79%;
    top: 45.86%;
    right: 2.82%;
    bottom: 53.94%;
    left: 32.39%;
    background-color: var(--lightgray);
  }
  .divider11 {
    position: absolute;
    height: 0.2%;
    width: 64.79%;
    top: 81.21%;
    right: 2.82%;
    bottom: 18.59%;
    left: 32.39%;
    background-color: var(--lightgray);
  }
  .div9 {
    position: absolute;
    top: 26.67%;
    left: 33.45%;
    letter-spacing: 0.1px;
    line-height: 20px;
    font-weight: 500;
  }
  .div10 {
    position: absolute;
    top: 65.66%;
    left: 33.45%;
    letter-spacing: 0.1px;
    line-height: 20px;
    font-weight: 500;
  }
  .description12 {
    position: absolute;
    top: 65.66%;
    left: 52.02%;
    line-height: 140%;
  }
  .description13 {
    position: absolute;
    height: 8.08%;
    width: 44.1%;
    top: 24.65%;
    left: 52.02%;
    letter-spacing: 0.25px;
    line-height: 20px;
    display: inline-block;
  }
  .div11 {
    position: absolute;
    top: 38.59%;
    left: 33.45%;
    letter-spacing: 0.1px;
    line-height: 20px;
    font-weight: 500;
  }
  .divider12 {
    position: absolute;
    height: 0.2%;
    width: 64.79%;
    top: 22.02%;
    right: 2.82%;
    bottom: 77.78%;
    left: 32.39%;
    background-color: var(--lightgray);
  }
  .div12 {
    position: absolute;
    top: 74.75%;
    left: 33.45%;
    letter-spacing: 0.46px;
    line-height: 20px;
    text-transform: uppercase;
    font-weight: 500;
  }
  .description14 {
    position: absolute;
    top: 74.75%;
    left: 52.02%;
    line-height: 140%;
  }
  .chips1InputbTextOnlyA15 {
    position: absolute;
    top: calc(50% - 60.5px);
    left: 648px;
    border-radius: var(--br-base);
    background-color: var(--color-whitesmoke-100);
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--material-theme-body-small-size);
    color: var(--darkgray);
  }
  .chips1InputbTextOnlyA16 {
    position: absolute;
    top: calc(50% - 60.5px);
    left: 591px;
    border-radius: var(--br-base);
    background-color: var(--black);
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--material-theme-body-small-size);
    color: var(--white);
  }
  .chips1InputbTextOnlyA17 {
    position: absolute;
    top: calc(50% - 60.5px);
    left: 705px;
    border-radius: var(--br-base);
    background-color: var(--color-whitesmoke-100);
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--material-theme-body-small-size);
    color: var(--darkgray);
  }
  .chips1InputbTextOnlyA18 {
    position: absolute;
    top: calc(50% - 60.5px);
    left: 762px;
    border-radius: var(--br-base);
    background-color: var(--black);
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--material-theme-body-small-size);
    color: var(--white);
  }
  .chips1InputbTextOnlyA19 {
    position: absolute;
    top: calc(50% - 60.5px);
    left: 960px;
    border-radius: var(--br-base);
    background-color: var(--color-whitesmoke-100);
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--material-theme-body-small-size);
    color: var(--darkgray);
  }
  .chips1InputbTextOnlyA20 {
    position: absolute;
    top: calc(50% - 60.5px);
    left: 879px;
    border-radius: var(--br-base);
    background-color: var(--color-whitesmoke-100);
    display: flex;
    flex-direction: row;
    padding: var(--padding-9xs);
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--material-theme-body-small-size);
    color: var(--darkgray);
  }
  .div13 {
    position: absolute;
    top: 37.98%;
    left: 7.04%;
    letter-spacing: 0.4px;
    line-height: 20px;
    font-weight: 500;
  }
  .groupParent1 {
    position: absolute;
    height: 10.51%;
    width: 22.54%;
    top: 56.57%;
    right: 70.42%;
    bottom: 32.93%;
    left: 7.04%;
    font-size: var(--material-theme-body-small-size);
  }
  .groupParent2 {
    position: absolute;
    height: 6.46%;
    width: 22.54%;
    top: 45.25%;
    right: 70.42%;
    bottom: 48.28%;
    left: 7.04%;
    font-size: var(--material-theme-body-small-size);
  }
  .bgContainer {
    position: absolute;
    height: 23.89%;
    width: 78.89%;
    top: 74.47%;
    right: 1.67%;
    bottom: 1.64%;
    left: 17.44%;
  }
  .div15 {
    position: absolute;
    width: calc(100% - 105px);
    top: calc(50% - 9px);
    left: 64px;
    letter-spacing: 0.1px;
    line-height: 21px;
    font-weight: 500;
    display: flex;
    align-items: center;
    height: 18px;
  }
  .icon50 {
    position: absolute;
    top: 8px;
    left: 216px;
    width: 24px;
    height: 24px;
    overflow: hidden;
  }
  .navigationItem {
    position: absolute;
    width: 100%;
    top: 152px;
    right: 0px;
    left: 0px;
    height: 40px;
  }
  .navigationItem1 {
    position: absolute;
    width: 100%;
    top: 296px;
    right: 0px;
    left: 0px;
    height: 40px;
  }
  .navigationItem2 {
    position: absolute;
    width: 100%;
    top: 200px;
    right: 0px;
    left: 0px;
    height: 40px;
  }
  .navigationItem3 {
    position: absolute;
    width: 100%;
    top: 248px;
    right: 0px;
    left: 0px;
    height: 40px;
  }
  .navigationItem4 {
    position: absolute;
    width: 100%;
    top: 104px;
    right: 0px;
    left: 0px;
    height: 40px;
  }
  .navigationItem5 {
    position: absolute;
    width: 100%;
    top: 392px;
    right: 0px;
    left: 0px;
    height: 40px;
  }
  .rectangle {
    position: absolute;
    height: 100%;
    width: calc(100% - 16px);
    top: 0px;
    right: 8px;
    bottom: 0px;
    left: 8px;
    border-radius: var(--br-9xs);
    background-color: var(--color-gray-100);
  }
  .vectorIcon {
    position: absolute;
    height: 60%;
    width: 9.38%;
    top: 20%;
    right: 84.38%;
    bottom: 20%;
    left: 6.25%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
  }
  .b9 {
    position: absolute;
    width: calc(100% - 105px);
    top: calc(50% - 9px);
    left: 64px;
    letter-spacing: 0.1px;
    line-height: 21px;
    display: flex;
    align-items: center;
    height: 18px;
  }
  .navigationItem6 {
    position: absolute;
    width: 100%;
    top: 344px;
    right: 0px;
    left: 0px;
    height: 40px;
  }
  .navigationItem7 {
    position: absolute;
    width: 100%;
    top: 440px;
    right: 0px;
    left: 0px;
    height: 40px;
  }
  .icon59 {
    position: absolute;
    top: 8px;
    left: 216px;
    width: 24px;
    height: 24px;
    overflow: hidden;
    display: none;
  }
  .navigationItem8 {
    position: absolute;
    width: 100%;
    top: 731px;
    right: 0px;
    left: 0px;
    height: 40px;
  }
  .koukokunushi {
    position: absolute;
    top: 0px;
    left: 48px;
    letter-spacing: 0.15px;
    line-height: 24px;
    font-weight: 500;
    display: -webkit-inline-box;
    align-items: center;
    overflow: hidden;
    text-overflow: ellipsis;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
    width: 176px;
  }
  .ellipseDiv {
    position: absolute;
    width: 100%;
    top: 0px;
    right: 0px;
    left: 0px;
    border-radius: 50%;
    background-color: var(--color-gray-200);
    height: 40px;
  }
  .image1Icon {
    position: absolute;
    width: calc(100% - 11.2px);
    top: 6.4px;
    right: 5.6px;
    left: 5.6px;
    max-width: 100%;
    overflow: hidden;
    height: 27.2px;
    object-fit: cover;
  }
  .ellipseParent {
    position: absolute;
    width: calc(100% - 184px);
    top: 0px;
    right: 184px;
    left: 0px;
    height: 40px;
  }
  .koukokunushiParent {
    position: absolute;
    width: calc(100% - 32px);
    top: 828px;
    right: 16px;
    left: 16px;
    height: 48px;
    font-size: var(--material-theme-title-medium-size);
  }
  .child {
    position: absolute;
    top: 787px;
    left: 0px;
    background-color: var(--color-darkslategray);
    width: 256px;
    height: 1px;
  }
  .div23 {
    position: absolute;
    top: 800px;
    left: 16px;
    font-size: var(--material-theme-body-small-size);
    letter-spacing: 0.4px;
    line-height: 16px;
  }
  .image1Icon1 {
    position: absolute;
    top: 32px;
    left: 16px;
    width: 150px;
    height: 40px;
    object-fit: cover;
  }
  .icon60 {
    position: absolute;
    height: 2.67%;
    width: 9.38%;
    top: 17.78%;
    right: 84.38%;
    bottom: 79.56%;
    left: 6.25%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
  }
  .icon61 {
    position: absolute;
    height: 2.67%;
    width: 9.38%;
    top: 33.78%;
    right: 84.38%;
    bottom: 63.56%;
    left: 6.25%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
  }
  .icon62 {
    position: absolute;
    height: 2.67%;
    width: 9.38%;
    top: 23.11%;
    right: 84.38%;
    bottom: 74.22%;
    left: 6.25%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
  }
  .icon63 {
    position: absolute;
    height: 2.67%;
    width: 9.38%;
    top: 28.44%;
    right: 84.38%;
    bottom: 68.89%;
    left: 6.25%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
  }
  .icon64 {
    position: absolute;
    height: 2.67%;
    width: 9.38%;
    top: 12.44%;
    right: 84.38%;
    bottom: 84.89%;
    left: 6.25%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
  }
  .icon65 {
    position: absolute;
    height: 2.67%;
    width: 9.38%;
    top: 44.44%;
    right: 84.38%;
    bottom: 52.89%;
    left: 6.25%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
  }
  .icon66 {
    position: absolute;
    height: 2.67%;
    width: 9.38%;
    top: 39.11%;
    right: 84.38%;
    bottom: 58.22%;
    left: 6.25%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
  }
  .icon67 {
    position: absolute;
    height: 2.67%;
    width: 9.38%;
    top: 49.78%;
    right: 84.38%;
    bottom: 47.56%;
    left: 6.25%;
    max-width: 100%;
    overflow: hidden;
    max-height: 100%;
  }
  .div14 {
    position: absolute;
    top: 0px;
    left: 0px;
    background-color: var(--black);
    width: 256px;
    height: 900px;
    overflow: hidden;
    color: var(--color-gray-200);
  }
  .bg6 {
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0%;
    right: 0%;
    bottom: 0%;
    left: 0%;
    background-color: var(--white);
    border-bottom: 1px solid var(--lightgray);
    box-sizing: border-box;
  }
  .b10 {
    position: absolute;
    top: 30%;
    left: 2.03%;
    line-height: 32px;
  }
  .heading {
    position: absolute;
    top: 0px;
    left: 256px;
    width: 1184px;
    height: 80px;
    font-size: var(--material-theme-headline-small-size);
  }
  .k10 {
    position: relative;
    background-color: var(--background);
    width: 100%;
    height: 2072px;
    overflow: hidden;
    text-align: left;
    font-size: var(--medium-14-size);
    color: var(--black);
    font-family: var(--components-button-small);
  }
</style>
