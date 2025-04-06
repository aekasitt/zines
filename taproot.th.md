<zine-page class='left'>
  <page-num>
    8
  </page-num>
  <br />
  <h2>
    ขอบคุณที่ให้เวลาอ่าน!
  </h2>
  <p>
    นี่เป็นแค่ภาพรวมสั้น ๆ ของแท็พรูท หวังว่าคุณได้อ่านอย่างเพลิดเพลิน
    พร้อมเรียนรู้เพิ่มเติมไหม ? อยากปรินท์นิตยสารกะทัดรัดฉบับนี้รีเปล่า ? ไปดู
  </p>
  <br /><br /><br /><br /><br />
  <img
    alt='Sorceress'
    src='./static/sorceress.svg'
    style='position: absolute; left: 2cm; top: 4.8cm; width: 6.4cm;'
    >
  <br /><br /><br /><br /><br />
  <p class='text-center'>
    <strong>
      https://satsie.dev/zines
    </strong>
  </p>
  <p class='text-center'>
    เพื่อทรัพยากรเสริม และเนื้อหาไม่ใกล้ไม่ไกลไปจาก
    สารสาส์นฉบับนี้
  </p>
</zine-page>

<zine-page class='right'>
  <img
    alt="Satsie's Pocket Guide"
    src='./static/taproot-satsies-pocket-guide.th.svg'
    style='position: absolute; left: 1cm; top: 2.4cm; height: 4cm;'
    >
  <img
    alt='Sir'
    src='./static/sir.svg'
    style='position: absolute; left: 2cm; top: 2.8cm; width: 6.4cm;'
    >
  <br /><br /><br /><br /><br />
  <br /><br /><br /><br /><br />
  <br /><br /><br /><br /><br />
  <br />
  <h1 style='margin: 0 auto; padding: .4cm .4cm;'>
    แท็พรูท
  </h1>
  <p class='text-center' style='margin-bottom: 0; margin-top: 0;'>
    ภาพรวมกะทัดรัดสำหรับบิทคอยน์อัพเกรด
    <br />
    นามว่าแท็พรูท
  </p>
</zine-page>

<zine-page class='left'>
  <page-num>
    6
  </page-num>
<table class='contents-centered'>
    <tr class='lean'>
      <td
        class='lean seamless'
        colspan='3'
        style='font-size: .64cm; letter-spacing: -.24cm; opacity: .4; transform: scale(1.12) translate(-1.2%);'
        >
        ～～～～～～～～～～～～～～～～
      </td>
    </tr>
    <tr style='margin: auto 0;'>
      <td
        class='lean seamless'
        style='font-size: .64cm; letter-spacing: -.24cm; line-height: .24cm; opacity: .4; transform: rotate(-90deg) translate(-10%);'
        >
        〜〜〜
      </td>
      <td class='lean seamless text-center' style='font-size: .36cm;'>
        แท็พรูทอัปเกรดมีส่วนประกอบ 3 ชิ้น
      </td>
      <td
        class='lean seamless'
        style='font-size: .64cm; letter-spacing: -.24cm; line-height: .24cm; opacity: .4; transform: rotate(-90deg) translate(-10%);'
        >
        〜〜〜
      </td>
    </tr>
    <tr class='lean'>
      <td
        class='lean seamless'
        colspan='3'
        style='font-size: .64cm; letter-spacing: -.24cm; opacity: .4; transform: scale(1.12) translate(-1.2%);'
        >
        ～～～～～～～～～～～～～～～～
      </td>
    </tr>
  </table>
  <ul class='text-left' style='padding: 0 2cm;'>
    <li>
      BIP-34Ø: กลไกไขรหัสชนอร์
      <span class='text-small'>
        (Schnorr)
      </span>
    </li>
    <li>
      BIP-341:
      <span class='text-small'>
        เมอร์เคิ่ลไลซ์แอ๊บแสตร็กท์ซินแทคส์ทรี (MAST)
      </span>
      + แท๊พรูท
    </li>
    <li>
      BIP-342: แท๊พสคริปท์
    </li>
  </ul>
  <p class='text-center'>
    เมื่อมีการพูดถึงแท็พรูท ในบริบททั่วไป รวมถึงวิธีที่เราได้กล่าวถึงมัน
    ณ ตอนนี้ โดยปกติแล้วมักจะหมายถึงทั้ง 3 สิ่งนี้โดยรวมกัน
  </p>
  <p class='text-center'>
    มาดูพวกมันอย่างใกล้ชิดกัน !!
  </p>
  <p>
    <strong>
      ☆ BIP-34Ø: กลไกไขรหัสชนอร์ ☆
    </strong>
    <br />
    This BIP introduces Schnorr, a new signature scheme.
    <br />
    <br />
    Compared with ECDSA, the other signature scheme <bitcoin></bitcoin>
    uses, Schnorr signatures are more secure, easier to work with,
    and slightly more efficient.
  </p>
</zine-page>

<zine-page class='right'>
  <page-num>
    3
  </page-num>
  <p>
    <strong>
      ☆ การตรวจสอบลายเซ็นแบบจับกลุ่ม ☆
    </strong>
  </p>
  <p class='text-left text-squeezed'>
    การตรวจสอบลายเซ็นดิจิทัลโดยปกติจำเป็นต้องใช้การคำนวณซับซ้อนจากสมองกลคอมพิวเตอร์
    ปัจจุบันเราสามารถจับกลุ่มลายเซ็นหลากหลาย ผ่านกระบวนการครวจสอบ
    เป็นกลุ่มก้อนเดียวกันได้ แทนที่การตรวจสอบทีละรายการ
  </p>
  <img
    alt='Signature A'
    src='./static/signature.th.svg'
    style='position: absolute; left: 1cm; top: 5.2cm; width: 2.4cm;'
    >
  <img
    alt='Signature B'
    src='./static/signature.th.svg'
    style='position: absolute; left: 1.6cm; top: 6cm; width: 2.4cm;'
    >
  <img
    alt='Signature B'
    src='./static/signature.th.svg'
    style='position: absolute; left: 2.2cm; top: 6.8cm; width: 2.4cm;'
    >
  <img
    alt='Arrow right'
    src='./static/arrow.svg'
    style='position: absolute; left: 4.8cm; top: 6cm; transform: scaleX(-1) rotate(-90deg); width: 1cm;'
    >
  <img
    alt='Musig'
    src='./static/musig.th.svg'
    style='position: absolute; right: 1cm; top: 5.2cm; width: 3cm;'
    >
  <br />
  <br />
  <br />
  <br />
  <br />
  <p>
    <strong>
      ☆ Better privacy while spending ☆
    </strong>
  </p>
  <p>
    <bitcoin></bitcoin> allows you to specify multiple ways to
    spend a coin. Prior to Taproot, all these ways had to be
    made public when the coin was spent. This is bad for privacy,
    especially for coins with unique spending rules, making them
    easy to identify.
  </p>
</zine-page>

<zine-page class='left'>
  <page-num>
    2
  </page-num>
  <table class='contents-centered'>
    <tr class='lean'>
      <td
        class='lean seamless'
        colspan='3'
        style='font-size: .64cm; letter-spacing: -.24cm; opacity: .4; transform: scale(1.25) translate(-1.2%);'
        >
        ～～～～～～～～～～～～～
      </td>
    </tr>
    <tr style='margin: auto 0;'>
      <td
        class='lean seamless'
        style='font-size: .64cm; letter-spacing: -.24cm; line-height: .24cm; opacity: .4; transform: rotate(-90deg) translate(-10%);'
        >
        〜〜〜
      </td>
      <td class='lean seamless text-center' style='font-size: .36cm;'>
        What is the Taproot Upgrade?
      </td>
      <td
        class='lean seamless'
        style='font-size: .64cm; letter-spacing: -.24cm; line-height: .24cm; opacity: .4; transform: rotate(-90deg) translate(-10%);'
        >
        〜〜〜
      </td>
    </tr>
    <tr class='lean'>
      <td
        class='lean seamless'
        colspan='3'
        style='font-size: .64cm; letter-spacing: -.24cm; opacity: .4; transform: scale(1.25) translate(-1.2%);'
        >
        ～～～～～～～～～～～～～
      </td>
    </tr>
  </table>
  <p class='text-center'>
    Taproot is a set of improvements that allow <bitcoin></bitcoin> to be used
    in a more scalable and private ways.
  </p>
  <p class='text-center'>
    Activation date: November 2021
    <br />
    Block height: 709,632.
  </p>
  <table class='contents-centered'>
    <tr class='lean'>
      <td
        class='lean seamless'
        colspan='3'
        style='font-size: .64cm; letter-spacing: -.24cm; opacity: .4; transform: scale(1.25) translate(-1.2%);'
        >
        ～～～～～～～～～～～～～～～
      </td>
    </tr>
    <tr style='margin: auto 0;'>
      <td
        class='lean seamless'
        style='font-size: .64cm; letter-spacing: -.24cm; line-height: .24cm; opacity: .4; transform: rotate(-90deg) translate(-10%);'
        >
        〜〜〜
      </td>
      <td class='lean seamless text-center' style='font-size: .36cm;'>
        <strong>
          Taproot enables some cool features
        </strong>
      </td>
      <td
        class='lean seamless'
        style='font-size: .64cm; letter-spacing: -.24cm; line-height: .24cm; opacity: .4; transform: rotate(-90deg) translate(-10%);'
        >
        〜〜〜
      </td>
    </tr>
    <tr class='lean'>
      <td
        class='lean seamless'
        colspan='3'
        style='font-size: .64cm; letter-spacing: -.24cm; opacity: .4; transform: scale(1.25) translate(-1.2%);'
        >
        ～～～～～～～～～～～～～～～
      </td>
    </tr>
  </table>
  <p class='text-center text-squeezed' style='padding: 0;'>
    <strong>
      ☆ Key and signature aggregation (MuSig) ☆
    </strong>
  </p>
  <p class='text-squeezed'>
    If you have public keys A, B and C, they can be combined into one.
    The same is true for the corresponding signatures. 
  </p>
  <img
    alt='Key A'
    src='./static/old-key-a.th.svg'
    style='position: absolute; left: .4cm; bottom: 2.6cm; width: 1.2cm;'
    >
  <img
    alt='Operator Add'
    src='./static/operator-add.svg'
    style='position: absolute; left: 1.6cm; bottom: 2.6cm; width: 1.2cm;'
    >
  <img
    alt='Key B'
    src='./static/old-key-b.th.svg'
    style='position: absolute; left: 2.8cm; bottom: 2.6cm; width: 1.2cm;'
    >
  <img
    alt='Operator Add again'
    src='./static/operator-add.svg'
    style='position: absolute; left: 4cm; bottom: 2.6cm; width: 1.2cm;'
    >
  <img
    alt='Key C'
    src='./static/old-key-c.th.svg'
    style='position: absolute; left: 5.2cm; bottom: 2.6cm; width: 1.2cm;'
    >
  <img
    alt='Equal'
    src='./static/operator-equal.svg'
    style='position: absolute; left: 6.4cm; bottom: 2.6cm; width: 1.2cm;'
    >
  <img
    alt='Key ABC'
    src='./static/old-key-abc.th.svg'
    style='position: absolute; left: 7.6cm; bottom: 2.6cm; width: 1.72cm;'
    >
  <br />
  <br />
  <p class='text-squeezed'>
    This means complex multisignature spends can look like ones that only
    involves 1 key.
  </p>
</zine-page>

<zine-page class='right'>
  <page-num>
    7
  </page-num>
  <p class='text-squeezed'>
    <strong>
      ☆ BIP-341: Script Trees + Taproot ☆
    </strong>
    <br />
    This BIP is made of 2 thigs:
  <p>
  <ol class='text-left text-squeezed' style='padding: 0 1.6cm;'>
    <li>
      <strong>
        Script trees:
      </strong>
      Tree-like data structures used to compactly encode multiple scripts.
      In this BIP, each leaf represents a single script and only one leaf
      may be chosen by the spender. The spender is responsible for showing
      the path of the leaf (AKA the "Merkle branch").
    </li>
    <li>
      <strong>
        Taproot:
      </strong>
      A technique that allows a coin to be spent by public key OR by script.
      Taproot leverages the power of MAST and Schnorr to make transactions more
      <strong>
        flexible, private and efficient.
      </strong>
      With Taproot, you can set up many different spending constraints, but only
      reveal the one that is used!
    </li>
  </ol>
  <p class='text-squeezed'>
    <strong>
      ☆ BIP-342: Tapscript ☆
    </strong>
    <br />
    Script is the <s>terribly uncreative</s>
    name for <bitcoin></bitcoin>'s smart contract language. Tapscript is an
    upgraded scripting language that supports Schnorr and Taproot.
  <p>
</zine-page>

<zine-page class='left'>
  <page-num>
    4
  </page-num>
  <p>
    With Taproot, the only thing that needs to be public is the specific
    way in which a coin was spent, not all other possibilities. This means:
  </p>
  <ol class='text-left' style='padding: 0 2cm;'>
    <li>
      ลดการเปลืองดาต้าบนบล็อก และ
    </li>
    <li>
      ปกป้องสิทธิสันโดษมากกว่าเดิม
    </li>
  </ol>
  <p class='text-squeezed'>
    <strong>
      Together, many features contribute to what is perhaps Taproot's most
      impressive use case: making many different ways of spending <bitcoin></bitcoin>
      indistinguishable from one another. It doesn't matter how simple or
      complex the spending rules are.
    </strong>
  </p>
  <table class='contents-centered'>
    <tr class='lean'>
      <td
        class='lean seamless'
        colspan='3'
        style='font-size: .64cm; letter-spacing: -.24cm; opacity: .4; transform: scale(1.12) translate(-2%);'
        >
        ～～～～～～～～～～
      </td>
    </tr>
    <tr style='margin: auto 0;'>
      <td
        class='lean seamless'
        style='font-size: .64cm; letter-spacing: -.24cm; line-height: .24cm; opacity: .4; transform: rotate(90deg) translate(-10%);'
        >
        〜〜〜
      </td>
      <td class='lean seamless text-center' style='font-size: .36cm;'>
        <strong>
          แท็พรูทปะทะเส็กวิท
        </strong>
      </td>
      <td
        class='lean seamless'
        style='font-size: .64cm; letter-spacing: -.24cm; line-height: .24cm; opacity: .4; transform: rotate(-90deg) translate(-10%);'
        >
        〜〜〜
      </td>
    </tr>
    <tr class='lean'>
      <td
        class='lean seamless'
        colspan='3'
        style='font-size: .64cm; letter-spacing: -.24cm; opacity: .4; transform: scale(1.12) translate(-2%);'
        >
        ～～～～～～～～～～
      </td>
    </tr>
  </table>
  <p>
    เส็กวิท (SegWit) ก็คืออัปเกรดตัวบึ้มที่มาก่อนแท็พรูท (Taproot)
  </p>
  <img
    alt='SegWit and Taproot Timeline'
    src='./static/segwit-taproot-timeline.th.svg'
    style='position: absolute; left: 1.6cm; bottom: 1cm; width: 7.2cm;'
    >
</zine-page>

<zine-page class='right'>
  <page-num>
    5
  </page-num>
  It contains many things, including a new version
  <br />
  field to use with transaction output scripts
  <hr />
  <p class='text-center text-squeezed'>
    For SegWit this value is set to "Ø" ("SegWit vØ").
    For Taproot, it's set to "1". This is why you'll sometimes
    see Taproot scripts referred to as "SegWit V1".
  </p>
  <hr />
  SegWit and Taproot are separate upgrades that
  <br />
  result in different transaction output types.
  <br />
  Taproot builds on the foundation SegWit created.
  </p>
  <table class='contents-centered'>
    <tr class='lean'>
      <td
        class='lean seamless'
        colspan='3'
        style='font-size: .64cm; letter-spacing: -.24cm; opacity: .4; transform: scale(1.12) translate(-1.2%);'
        >
        ～～～～～～～～～～～～～～～～～
      </td>
    </tr>
    <tr style='margin: auto 0;'>
      <td
        class='lean seamless'
        style='font-size: .64cm; letter-spacing: -.24cm; line-height: .24cm; opacity: .4; transform: rotate(-90deg) translate(-10%);'
        >
        〜〜〜
      </td>
      <td class='lean seamless text-center' style='font-size: .36cm;'>
        The Taproot Upgrade was a Soft Fork
      </td>
      <td
        class='lean seamless'
        style='font-size: .64cm; letter-spacing: -.24cm; line-height: .24cm; opacity: .4; transform: rotate(-90deg) translate(-10%);'
        >
        〜〜〜
      </td>
    </tr>
    <tr class='lean'>
      <td
        class='lean seamless'
        colspan='3'
        style='font-size: .64cm; letter-spacing: -.24cm; opacity: .4; transform: scale(1.12) translate(-1.2%);'
        >
        ～～～～～～～～～～～～～～～～～
      </td>
    </tr>
  </table>
  <p class='text-squeezed'>
    This means the upgrade narrows consensus rules, or constrains
    the rules of the system. Soft forks require majority hashpower
    from miners but the upgrade is optional for everyone else.
    Any behavior that was invalid before continues to be invalid,
    and nodes running older version of <bitcoin></bitcoin> continue
    to be compatible with newer versions.
  </p>
</zine-page>