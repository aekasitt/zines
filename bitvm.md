<zine-page class='left'>
  <page-num>
    8
  </page-num>
</zine-page>

<zine-page class='right'>
  <img
    alt="Satsie's Pocket Guide"
    src='./static/gurus-gazette-bitvm.svg'
    style='position: absolute; left: 0cm; top: .8cm; height: 4cm;'
    >
  <img
    alt='Bthulu'
    src='./static/bthulu.svg'
    style='position: absolute; left: 1.4cm; top: 4.2cm; height: 7.2cm;'
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
  <br />
  <br />
  <br />
  Demystify <bitcoin></bitcoin>'s Latest
  <hr style='width: 40%'/>
  one ought to know
  <br />
  without the hype
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
  <table class='contents-centered'>
    <tr>
      <td>
        <small-splash-left></small-splash-left>
      </td>
      <td>
        <p>
          But first,
          <strong>
            Covenants
          </strong>
        </p>
      </td>
      <td>
        <small-splash-right></small-splash-right>
      </td>
    </tr>
  </table>
  <table class='contents-centered'>
    <tr class='lean'>
      <td
        class='lean seamless'
        colspan='3'
        style='
          font-size: .48cm; letter-spacing: -.18cm; opacity: .6; transform: translate(-1%, 50%);
        '>
        ～～～～～～～～～～～～～～～～～～～～～～～～～
      </td>
    </tr>
    <tr style='margin: auto 0;'>
      <td
        class='lean seamless'
        style='
          font-size: .84cm; letter-spacing: -.32cm; opacity: .4; transform: rotate(90deg) translate(-8%); white-space: nowrap;
        '>
        ～～～～～
      </td>
      <td class='lean seamless text-center text-small text-squeezed'>
        Covenants are a category of proposed changes to <bitcoin></bitcoin>'s
        consensus rules that would allow a script to prevent an authorized spender
        from spending to certain other scripts.
      </td>
      <td
        class='lean seamless'
        style='
          font-size: .84cm; letter-spacing: -.32cm; opacity: .4; transform: rotate(-90deg) translate(-8%); white-space: nowrap;
        '>
        ～～～～～
      </td>
    </tr>
    <tr class='lean'>
      <td
        class='lean seamless'
        colspan='3'
        style='
          font-size: .48cm; letter-spacing: -.18cm; opacity: .6; transform: translate(-1%, -50%);
        '>
        ～～～～～～～～～～～～～～～～～～～～～～～～～
      </td>
    </tr>
  </table>
  <img
    alt='Byzantine Generals forming Covenant'
    src='./static/byzantine-generals.svg'
    style='position: absolute; left: 2.8cm; top: 5.6cm; width: 4.8cm;'
    >
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <br />
  <p class='text-center'>
    We do not yet have Covenants on <bitcoin></bitcoin>,
    but we can emulate it.
  </p>
  <p class='text-small'>
    Covenant emulation in BitVM2 is a workaround that uses a signer
    committee to mimic advanced spending conditions not natively supported
    by <bitcoin></bitcoin>, introducing a small trust assumption.
  </p>
</zine-page>

<zine-page class='left'>
  <page-num>
    2
  </page-num>
  <h3>
    BitVM is a bridge between <bitcoin></bitcoin> and a sidesystem. 
  </h3>
  <img
    alt='Golden Gate bridge'
    src='./static/golden-gate.svg'
    style='position: absolute; left: 3.2cm; top: 2cm; width: 3.6cm;'
    >
  <br />
  <br />
  <br />
  <br />
  <p>
    Generally, bridges are secured by a federated multisig where exit
    cannot be done unilaterally, but by approval of majority vote.
  </p>
  <table class='contents-centered'>
    <tr>
      <td>
        <small-splash-left></small-splash-left>
      </td>
      <td>
        <h2>
          BitVM is different !!
        </h2>
      </td>
      <td>
        <small-splash-right></small-splash-right>
      </td>
    </tr>
  </table>
  <p class='text-squeezed'>
    It is a 1-of-N trust model, in which as long as you have one live
    honest operator, you can withdraw on-chain. Users can bet on one
    honest operator instead of majority honest actors per federation.
  </p>
</zine-page>

<zine-page class='right'>
  <page-num>
    7
  </page-num>
  <h4>
    Rate of Innovations
  </h4>
  <table class='text-small' style='border: 0; margin: 0 auto;'>
    <thead style='border: 0;'>
      <tr style='border: 0;'>
        <th style='border: 0;'>PROTOCOL</th>
        <th style='border: 0;'>PREPROCESSING</th>
        <th style='border: 0;'>STORAGE</th>
        <th style='border: 0;'>ROUNDS</th>
      </tr>
    </thead>
    <tbody style='border: 0;'>
      <tr style='border: 0;'>
        <td colspan='4' style='border: 0;'>
          〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰〰
        </td>
      </tr>
      <tr style='border: 0;'>
        <td style='border: 0;'>
          BitVM
          <br />
          (gate-based)
        </td>
        <td style='border: 0;'>Weeks</td>
        <td style='border: 0;'>Terabytes</td>
        <td style='border: 0;'>~ 50</td>
      </tr>
      <tr style='border: 0;'>
        <td style='border: 0;'>BitVM</td>
        <td style='border: 0;'>Days</td>
        <td style='border: 0;'>Gigabytes</td>
        <td style='border: 0;'>~ 38</td>
      </tr>
      <tr style='border: 0;'>
        <td style='border: 0;'>BitVM2</td>
        <td style='border: 0;'>Minutes</td>
        <td style='border: 0;'>Megabytes</td>
        <td style='border: 0;'>1</td>
      </tr>
    </tbody>
  </table>
  <h3>
    Why are Rollups being discussed on <bitcoin></bitcoin> again?
  </h3>
  <p class='text-center'>
    Better than allowing bloatwares on the mainchain, BitVM clears the path for
    some important works in the cypherpunk world to emerge on <bitcoin></bitcoin>
    discussions.
  </p>
  <p class='text-justify text-sqeezed'>
    Independent teams rush to create Zero-Knowledge Proof Verifier on Bitcoin script
    and Tapscript again with the workaround presented by BitVM research.
  </p>
</zine-page>

<zine-page class='left'>
  <page-num>
    4
  </page-num>
  <h3 style='padding-bottom: 0; margin-bottom: 0;'>
    Why talk about Covenants when discussing BitVM ?
  </h3>
  <p class='text-center'>
    Because <bitcoin></bitcoin> is the only decentralized verifier in the world.
    The network verifies proofs, signatures and transactions without prejudice.
  </p>
  <p class='text-small' style='margin: 0 .8cm;'>
    Design decisions under <bitcoin></bitcoin>, including Turing-incompleteness
    within scripting language, allow every node to verify scripts efficiently
    within the 1,000 stack elements and 201 opcodes trustlessly.
  </p>
  <p class='text-center text-squeezed'>
    Both Covenants and BitVM challenge this limit, but BitVM does it
    without requiring changes to the <bitcoin></bitcoin> protocol, (not yet),
    but with a paradigm shift.
  </p>
  <h4>
    What can Bitcoiners do now, that they cannot before?
  </h4>
  <img
    alt='Bristol Circuit'
    src='./static/bristol-circuit.svg'
    style='position: absolute; bottom: .8cm; left: .4cm; height: 2cm;'
    >
  <img
    alt='Shielded Client-side Validation'
    src='./static/shielded-csv.svg'
    style='position: absolute; bottom: 1.2cm; left: 2cm; height: 2cm;'
    >
  <img
    alt='Proof System'
    src='./static/proof-system.svg'
    style='position: absolute; bottom: .6cm; left: 3cm; height: 2cm;'
    >
  <img
    alt='Arbitrary Computation'
    src='./static/arbitrary-computation.svg'
    style='position: absolute; bottom: 1cm; left: 4.2cm; height: 2cm;'
    >
  <img
    alt='Covenant Lite'
    src='./static/covenant-lite.svg'
    style='position: absolute; bottom: .6cm; left: 5.6cm; height: 2cm;'
    >
  <img
    alt='Bridge'
    src='./static/sidechain-bridge.svg'
    style='position: absolute; bottom: 1cm; left: 7.4cm; height: 2cm;'
    >
  <p
    class='text-center text-small'
    style='bottom: 2.2cm; left: .4cm; line-height: 1; position: absolute;'>
    Bristol
    <br/>
    Circuit
  </p>
  <p
    class='text-center text-small'
    style='bottom: .2cm; left: 1.4cm; line-height: 1; position: absolute;'
    >
    Shielded
    <br/>
    CSV
  </p>
  <p
    class='text-center text-small'
    style='bottom: 2.2cm; left: 2.6cm; line-height: 1; position: absolute;'
    >
    Proof
    <br/>
    Systems
  </p>
  <p
    class='text-center text-small'
    style='bottom: .2cm; left: 3.8cm; line-height: 1; position: absolute;'
    >
    Compute
    <br/>
    Anything
  </p>
  <p
    class='text-center text-small'
    style='bottom: 2.2cm; left: 5.2cm; line-height: 1; position: absolute;'
    >
    Covenant
    <br/>
    Lite
  </p>
  <p
    class='text-center text-small'
    style='bottom: .2cm; left: 7cm; line-height: 1; position: absolute;'
    >
    Side
    <br/>
    Layers
  </p>
</zine-page>

<zine-page class='right'>
  <page-num>
    5
  </page-num>
  <h2 style='margin-bottom: 0; padding-bottom: 0;'>
    Let's look at User-friendly Upgrades !!
  </h2>
  <img
    alt='Shielded Client-side Validation'
    src='./static/shielded-csv.svg'
    style='position: absolute; top: 1cm; left: 0; height: 4cm;'
    >
  <h4 style='margin-bottom: 0; margin-left: 1.8cm;'>
    Shielded Client-Side Validation
  </h4>
  <p class='text-justify text-squeezed' style='margin-bottom: 0; margin-left: 1.8cm;'>
    Transaction history is rich source of information to link transactions
  </p>
  <p style='margin-top: 0; padding-top: 0;'>
    and de-anonymizing users. Client-Side validation protocols, where the coin proof
    reveals the transaction history of the coin, offer certain privacy advantages over
    transparent blockchain transactions. Senders broadcast nullifiers to Receivers
    which contain full history of the coin.
  </p>
  <p class='text-left'>
    <strong>
    Known CSV Models in the wild
    </strong>
  </p>
  <ul class='text-left'>
    <li>
      RGB Protocol
    </li>
    <li>
      Lightning Labs' Taproot Assets
    </li>
  </ul>
  <p class='text-center'>
    With Shielded CSV on BitVM paradigm, nullifier footprints can be limited to 64-byte size
    and contain only validity proof without de-anonymyzing data.
  </p>
</zine-page>