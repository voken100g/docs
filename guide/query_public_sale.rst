.. _query_public_sale:

How to query Voken2.0 public-sale data
======================================

|logo_etherscan_verified| |logo_github| |logo_verified|

- Contract address is **0xeBbcC1e995Fd41338EFf305807d0Ded8ea2363A1**
- Deployed at `Tx Hash 0x92571d8b53af360945c55b2cc6606389...`_
- Block height `#8498075`_
- Open-sourced under the `GNU General Public License v3.0`_
- `View contract code on github repository`_
- `View contract on Etherscan.io`_

.. _Tx Hash 0x92571d8b53af360945c55b2cc6606389...:
   https://etherscan.io/tx/0x92571d8b53af360945c55b2cc660638996e54840e33995f69dc333bffd243636
.. _#8498075:
   https://etherscan.io/block/8498075
.. _GNU General Public License v3.0:
   https://github.com/voken100g/contracts/blob/master/LICENSE
.. _View contract code on github repository:
   https://github.com/voken100g/contracts/blob/master/VokenPublicSalePanel.sol
.. _View contract on Etherscan.io:
   https://etherscan.io/address/0xeBbcC1e995Fd41338EFf305807d0Ded8ea2363A1#readContract

.. |logo_github| image:: /_static/logos/github.svg
   :width: 36px
   :height: 36px

.. |logo_etherscan_verified| image:: /_static/logos/etherscan_verified.svg
   :width: 36px
   :height: 36px

.. |logo_verified| image:: /_static/logos/verified.svg
   :width: 36px
   :height: 36px


Here is the link for **Read the Contract**:
``https://etherscan.io/address/0xeBbcC1e995Fd41338EFf305807d0Ded8ea2363A1#readContract``

Click `here`_, then **Contract** => **Read Contract**

.. _here: https://etherscan.io/address/0xeBbcC1e995Fd41338EFf305807d0Ded8ea2363A1#readContract


Status of Voken2.0 public-sale
------------------------------

Function #1: **status**

.. image:: /_static/contract/public_sale_status.png
   :width: 80 %
   :align: center
   :alt: public_sale_status.png


Let's focus on the values:

.. code-block:: text

   stage            |uint16 :  3277
   season           |uint16 :  6
   etherUsdPrice    |uint256 :  200000000
   vokenUsdPrice    |uint256 :  33770
   shareholdersRatio|uint256 :  17730833
   txs              |uint256 :  1
   vokenIssued      |uint256 :  59224163
   vokenBonus       |uint256 :  59224163
   weiRewarded      |uint256 :  600000000000000
   usdRewarded      |uint256 :  2000000


.. NOTE::

   stage
      Stage number.

      ``3277`` means: It's in **Stage #3277**.


   season
      Season number.

      ``6`` means: It's in **Season #6**.


   etherUsdPrice
      Current Audit ETH Price, in USD, with 6 decimals.

      In this case, ``200000000`` means you can use `1 ETH` as **$ 200.000000 USD**, for now.


   vokenUsdPrice
      Current Voken price, in USD, with 6 decimals.

      ``33770`` means: Current Voken price is **$ 0.033770 USD** .


   shareholdersRatio
      Current shareholders ratio, with 8 decimals.

      ``17730833`` is **0.17730833**, means
      **17.730833%** of the last transaction ETH amount will be transferred to :ref:`voken2_shareholders_contract`.
      It is calculated by `Stage number`, if the Public-Sale goes into next stage, ratio increases.


   txs
      Transactions amount in this Voken Public-Sale.

      ``1`` means: There are **1 transaction** since the Voken Public-Sale started.


   vokenIssued
      Voken2.0 issued amount transferred already, with 6 decimals.

      ``59224163`` is **59.224163 Voken2.0**.


   vokenBonus
      Voken2.0 bonus amount transferred already, with 6 decimals.

      ``59224163`` is **59.224163 Voken2.0**.


   weiRewarded
      The amount of rewards, in ETH, with 18 decimals.

      ``600000000000000`` is **0.000600000000000000 ETH**.
