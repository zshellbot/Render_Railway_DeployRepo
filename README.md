## Deploy On Render (free acc)

- Render ဖွင့်ပြီး free signup လုပ်ပါ။
- dashboard.render.com ဖွင့်ပြီး new + ကို နှိပ် web service ကို ရွေးပါ
- Public Git repository နေရာတွင် ယခု repo link ထည့်ပါ။ branch ကို ယခု SimpleM
TB.v.1 ရွေးပါ
- name နေရာ ကြိုက်ရာထားပါ (ဒိနာမည်က base url မှာ ပြန်သုံးတာပါ)
- အောက်နားက advanced နှိပ်ပြီး Add Environment Variable ထပ်နှိပ်ပါ
- key နေရာတွင် **BOT_TOKEN** = ""
- **OWNER_ID** = "" တို့ဖြည့်ရန်။ 
- Bot token, Owner ID ယူနည်း [ဒီမှာကြည့်ပါ။](https://t.me/drivetalkchannel/161)
- **BASE_URL** = "" ဖြည့်ပါ။ base url တွင် render တွင်သုံးမည့် applink ထည့်ပါ။ ဥပမာ မိမိ render app ကို anasmltb0123 ဆိုလျှင် base url တွင် https://anasmltb0123.onrender.com ဟုဖြည့်ရမည်
- **SERVER_PORT** = ""  ကို **80** ထားပါ
- **env vars ဒီ ၄ ခုပဲ ဖြည့်ဖို့လိုပါတယ်**
- ပြီးလျှင် အောက်ဆုံးနားက create web service အပြာရောင် ကို နှိပ်ပြီး ခဏေစာင့်ပါ
- terminal box တက်လာပြီး install ပါမည်။ Bot Start စာပေါ်လာလျှင် စသုံးလို့ရပါပြီ။

## Deploy On Railway

- railway acc sign in ပြီး **+New Project** ကိုနှိပ်ပါ
- Github acc connect မလုပ်ရသေးလျှင် connect ပါ
- connect ပြီးလျှင် **Deploy From Github repo** ကိုရွေးပါ
- ယခု repo ကို fork ထားသော မိမိ repo name ရွေးပါ
- **+ variables** နှိပ်ပါ
- **BOT_TOKEN, OWNER_ID** ဒီ၂ ခုသာ ဖြည့်ပါ။
- ပြီးလျှင် setting tab မှ Automatic Deployments အောက်တွင် simple MLTB branch ရွေးလိုက်ပါ
- Deployment tab ပြန်သွားပါ  ခဏစောင့်ပြီးလျှင် bot တက်ပါပြီ
