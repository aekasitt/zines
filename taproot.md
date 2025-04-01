<zine-page class='left'>
  <page-num>
    8
  </page-num>
</zine-page>

<zine-page class='right'>
  <img
    alt="Satsie's Pocket Guide"
    src='./static/taproot-satsies-pocket-guide.svg'
    style='position: absolute; left: 1cm; top: 2.4cm; height: 4cm;'
    >
  <img
    alt='Sir'
    src='./static/sir.svg'
    style='position: absolute; left: 2cm; top: 2.8cm; width: 6.4cm;'
    >
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <h1 style='margin: 0 auto; padding: .4cm .4cm;'>
    TAPROOT
  </h1>
  <p class='text-center' style='margin-bottom: 0; margin-top: 0;'>
    A SHORT OVERVIEW OF BITCOIN'S
    <br />
    TAPROOT UPGRADE
  </p>
</zine-page>

<zine-page class='left'>
  <page-num>
    6
  </page-num>
</zine-page>

<zine-page class='right'>
  <page-num>
    3
  </page-num>
  <p>
    <strong>
      ☆ Batch signature validation ☆
    </strong>
  </p>
  <p>
    Validating digital signatures usually requires a lot of efforts
    from a computer's CPU. Now transaction signatures can be grouped
    together and validated as one unit, instead of one by one.
  </p>
  <img
    alt='Signature A'
    src='./static/signature.svg'
    style='position: absolute; left: 1cm; top: 4.6cm; width: 2.4cm;'
    >
  <img
    alt='Signature B'
    src='./static/signature.svg'
    style='position: absolute; left: 1.6cm; top: 5.4cm; width: 2.4cm;'
    >
  <img
    alt='Signature B'
    src='./static/signature.svg'
    style='position: absolute; left: 2.2cm; top: 6.2cm; width: 2.4cm;'
    >
  <img
    alt='Arrow right'
    src='./static/arrow.svg'
    style='position: absolute; left: 4.8cm; top: 5.4cm; transform: scaleX(-1) rotate(-90deg); width: 1cm;'
    >
  <img
    alt='Musig'
    src='./static/musig.svg'
    style='position: absolute; right: 1cm; top: 4.6cm; width: 3cm;'
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
    Block height: 709,631.
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
    src='./static/old-key-a.svg'
    style='position: absolute; left: .4cm; bottom: 2.6cm; width: 1.2cm;'
    >
  <img
    alt='Operator Add'
    src='./static/operator-add.svg'
    style='position: absolute; left: 1.6cm; bottom: 2.6cm; width: 1.2cm;'
    >
  <img
    alt='Key B'
    src='./static/old-key-b.svg'
    style='position: absolute; left: 2.8cm; bottom: 2.6cm; width: 1.2cm;'
    >
  <img
    alt='Operator Add again'
    src='./static/operator-add.svg'
    style='position: absolute; left: 4cm; bottom: 2.6cm; width: 1.2cm;'
    >
  <img
    alt='Key C'
    src='./static/old-key-c.svg'
    style='position: absolute; left: 5.2cm; bottom: 2.6cm; width: 1.2cm;'
    >
  <img
    alt='Equal'
    src='./static/operator-equal.svg'
    style='position: absolute; left: 6.4cm; bottom: 2.6cm; width: 1.2cm;'
    >
  <img
    alt='Key ABC'
    src='./static/old-key-abc.svg'
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
</zine-page>

<zine-page class='left'>
  <page-num>
    4
  </page-num>
</zine-page>