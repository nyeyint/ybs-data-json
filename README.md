# YBS Data - Simplify JSON
<div style="font-family: line-height: 1.5em; myanmar3, padauk, 'noto sans myanmar', pyidaungsu, 'myanmar text'">
ရန္ကုန္တိုင္းေဒသႀကီး အမ်ားျပည္သူ သယ္ယူပို႔ေဆာင္ေရးႀကီးၾကပ္မႈ အာဏာပိုင္အဖြဲ႕ (YRTA) မွ တရားဝင္ ထုတ္ျပန္ထားသည့္ YBS Open Data (ybs_000115) အား App မ်ား Website မ်ားတြင္ အသင့္ အသုံးျပဳႏိုင္ေသာ JSON Data အျဖစ္ ေျပာင္းလဲ ထားျခင္းျဖစ္သည္။
<br><br>
<ul>
	<li>အဓိကအခ်က္အလက္မ်ားႏွင့္ အေသးစိတ္အခ်က္အလက္မ်ားကို ခြဲထုတ္ထားသည္
	<li>String မ်ားအား JSON ျဖစ္ေအာင္ Parse လုပ္ထားသည္
	<li>Whitespace အပိုမ်ား ဖယ္ထုတ္သန႔္စင္ထားသည္
	<li>စာလုံးေပါင္းမ်ားအခ်ိဳ႕ျပင္ဆင္ထားၿပီး ဆက္လက္ျပင္ဆင္ရန္ ရည္႐ြယ္သည္
	<li>မွတ္တိုင္အမည္ကြဲမ်ား တြဲဖက္ထည့္သြင္းထားသည္၊ ဆက္လက္ျဖည့္စြက္ သြားရန္ ရည္႐ြယ္သည္
	<li>တည္ေနရာတူ မွတ္တိုင္ကြဲမ်ားအား ခ်ိတ္ဆက္ထားသည္
</ul>
</div>
<br>
<img src="http://i.imgur.com/Wmg1pf8.png">
<br>
## List of files
<div style="font-family: line-height: 1.5em;  myanmar3, padauk, 'noto sans myanmar', pyidaungsu, 'myanmar text'">
<ul style="line-height: 1.5em;">
	<li><code>bus-line-data-by-id.js</code>
	<span style="font-family: myanmar3, padauk, 'noto sans myanmar', pyidaungsu, 'myanmar text'">ယာဥ္လိုင္းအလိုက္ အေျချပဳၿမိဳ႕နယ္၊ ေဒသႏွင့္ အမ်ိဳးအစားမ်ား ပါဝင္သည္</span>
	<li><code>bus-stop-data-by-id.js</code>
	<span style="font-family: myanmar3, padauk, 'noto sans myanmar', pyidaungsu, 'myanmar text'">မွတ္တိုင္အမွတ္အလိုက္ အမည္၊ အမည္ကြဲ၊ လမ္းႏွင့္ တည္ေနရာမ်ား ပါဝင္သည္</span>
	<li><code>bus-stop-ids-of-lines.js</code>
	<span style="font-family: myanmar3, padauk, 'noto sans myanmar', pyidaungsu, 'myanmar text'">ယာဥ္လိုင္းအမွတ္အလိုက္ ျဖတ္သန္းသြားေရာက္သည့္ မွတ္တိုင္အမွတ္မ်ား ပါဝင္သည္</span>
	<li><code>bus-stop-names-of-lines.js </code>
	<span style="font-family: myanmar3, padauk, 'noto sans myanmar', pyidaungsu, 'myanmar text'">ယာဥ္လိုင္းအမွတ္အလိုက္ ျဖတ္သန္းသြားေရာက္သည့္ မွတ္တိုင္အမည္မ်ား ပါဝင္သည္</span>
	<li><code>lines-of-bus-stops.js</code>
	<span style="font-family: myanmar3, padauk, 'noto sans myanmar', pyidaungsu, 'myanmar text'">မွတ္တိုင္အလိုက္ ျဖတ္သန္းသြားသည့္ ယာဥ္လိုင္းမ်ား ပါဝင္သည္</span>
</ul>
</div>

### Todo
<div style="font-family: line-height: 1.5em;  myanmar3, padauk, 'noto sans myanmar', pyidaungsu, 'myanmar text'">
* မွတ္တိုင္အလိုက္ အခ်က္အလက္မ်ားတြင္ ဦးတည္ရာအၫႊန္း (သို႔) လမ္း၏ မည္သည့္ဘက္တြင္ တည္ရွိသည္ကို ထည့္သြင္းသင့္သည္။
</div>

## Note
<div style="font-family: line-height: 1.5em;  myanmar3, padauk, 'noto sans myanmar', pyidaungsu, 'myanmar text'">
မွတ္တိုင္အလိုက္ ျဖတ္သန္းသြားသည့္ ယာဥ္လိုင္းမ်ား ေဖာ္ျပရာတြင္၊ တည္ေနရာတူညီသည္ အျခားမွတ္တိုင္မ်ားသို႔ ေရာက္ရွိသည့္ ယာဥ္လိုင္းမ်ားအားလည္း တြဲဖက္ေပးထားသည္။ <code>lines-of-bus-stops.js</code> တြင္ေလ့လာပါ။

<img src="http://i.imgur.com/AITZoYo.png">

ဥပမာ - ၿမိဳ႕ထဲသို႔သြားသည့္ "သီတာလမ္း" မွတ္တိုင္ႏွင့္ လမ္းတစ္ဘက္ျခမ္းရွိ တာေမြသို႔သြားသည့္ "သီတာလမ္း" မွတ္တိုင္တို႔သည္ မွတ္တိုင္အမွတ္ ကြဲျပားေသာ္လည္း တည္ေနရာ တစ္ခုတည္းျဖစ္သည္ဟု မွတ္ယူျခင္းျဖစ္ပါသည္။
</div>

## Route API
<div style="font-family: line-height: 1.5em;  myanmar3, padauk, 'noto sans myanmar', pyidaungsu, 'myanmar text'">
သြားေရာက္လိုသည့္ ခရီးစဥ္ အစမွတ္တိုင္ <code>id</code> ႏွင့္ အဆုံးမွတ္တိုင္ <code>id</code> ေပးလွ်င္ စီးရမည့္ ယာဥ္လိုင္းမ်ားအား ျပန္ေပးႏိုင္သည့္ လုပ္ေဆာင္ခ်က္ျဖစ္သည္။ အသုံးျပဳရန္ API URL မွာ ေအာက္ပါအတိုင္ျဖစ္သည္။
<br><br>
<code><a href="http://barseeyale.com/api/route/best/138/287">http://barseeyale.com/api/route/best/138/287</a></code>
<br><br>
<code>138</code> သည္ အစမွတ္တိုင္ (လမ္း ၃၀) ျဖစ္သည္။ <code>287</code> သည္ အဆုံးမွတ္တိုင္ (လွည္းတန္း) ျဖစ္သည္။ မိမိလိုအပ္သည့္ ခရီးစဥ္၏ အစမွတ္တိုင္၊ အဆုံးမွတ္တိုင္တို႔ႏွင့္ အစားထိုးအသုံးျပဳႏိုင္သည္။

ရရွိမည့္ရလဒ္နမူနာမွာ ေအာက္ပါအတိုင္းျဖစ္သည္။<br><br>
<pre style="background: black; color: white">

	{
		"type": 2,
		"line": ["58", "21"],
		"nos": [7, 13],
		"list": [
			["138", "137", "...", "122"],
			["122", "125", "...", "287"]
		],
		"names": ["ေမာ္တင္", "လွည္းတန္း"]
	}
</pre>

<ul>
	<li>
		<code>"type": 2</code> ဆိုသည္မွာ ႏွစ္ဆင့္စီးရမည္ဟု အဓိပၸါယ္ရသည္
	</li>
	<li>
		<code>"line": ["58", "21"]</code> ဆိုသည္မွာ ပထမအဆင့္ (၅၈) ကိုစီး၍၊ ဒုတိယအဆင့္ (၂၁) ကို ေျပာင္းစီးရမည္ဟု အဓိပၸါယ္ရသည္
	</li>
	<li>
		<code>"nos": [7, 13]</code> ဆိုသည္မွာ ပထမယာဥ္လိုင္း (၅၈) ကို (၇) မွတ္တိုင္စီး၍၊ ဒုတိယယာဥ္လိုင္း (၂၁) ကို (၁၃) မွတ္တိုင္ စီးရမည္ဟု အဓိပၸါယ္ရသည္
	</li>
	<li><code>"list"</code> ျဖင့္ ေဖာ္ျပထားသည္မ်ားမွာ မွတ္တိုင္စဥ္ အဆင့္ဆင့္ျဖစ္သည္</li>
	<li><code>"names": ["ေမာ္တင္", "လွည္းတန္း"]</code> ဆိုသည္မွာ ပထမယာဥ္လိုင္း (၅၈) ကို "ေမာ္တင္" ထိ စီးရမည္ျဖစ္ၿပီး၊ ဒုတိယယာဥ္လိုင္း (၂၁) ကို "လွည္းတန္း" ထိ စီးရမည္ဟု အဓိပၸါယ္ရသည္
</ul>

API ဆိုင္ရာ က်န္အခ်က္အလက္မ်ားကို <a href="http://barseeyale.com">barseeyale.com</a> တြင္ ဆက္လက္ေလ့လာႏိုင္သည္။
</div>

## Disclaimer
<div style="font-family: line-height: 1.5em;  myanmar3, padauk, 'noto sans myanmar', pyidaungsu, 'myanmar text'">
ဤအခ်က္အလက္မ်ားသည္ ရန္ကုန္တိုင္းေဒသႀကီး အမ်ားျပည္သူ သယ္ယူပို႔ေဆာင္ေရးႀကီးၾကပ္မႈ အာဏာပိုင္အဖြဲ႕ (YRTA) တရားဝင္ စီမံထိမ္းသိမ္း၍ ျဖန္႔ျဖဴးထားျခင္း <b>မဟုတ္ပါ</b>။ အခ်က္အလက္ တိက်မႈအားလည္ေကာင္း၊ ျပည့္စုံမႈအားလည္ေကာင္း အာမမခံပါ။
</div>

## License
<div style="font-family: line-height: 1.5em;  myanmar3, padauk, 'noto sans myanmar', pyidaungsu, 'myanmar text'">
ဤအခ်က္အလက္မ်ားအား YRTA Open Data License 1.0 ပါ ခြင့္ျပဳခ်က္ႏွင့္အညီ ျပင္ဆင္၍ ျပန္လည္ျဖန္႔ေဝသည္။ ဤအခ်က္အလက္မ်ားအား YRTA Open Data License 1.0 ပါ ခြင့္ျပဳခ်က္မ်ား၊ ကန႔္သန႔္ခ်က္မ်ားႏွင့္အညီ ရယူျခင္း၊ ျပင္ဆင္ျခင္း၊ ျဖန႔္ေဝျခင္းမ်ား ျပဳလုပ္ႏိုင္သည္။
</div><br><br>
http://data.yangonbus.com/license.html

## Remark
<small>Missing Bus Stop #200 in original source.</small>
