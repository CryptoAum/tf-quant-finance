<!--
This file is generated by a tool. Do not edit directly.
For open-source contributions the docs will be updated automatically.
-->

*Last updated: 2022-01-26.*

<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf_quant_finance.experimental.instruments" />
<meta itemprop="path" content="Stable" />
</div>

# Module: tf_quant_finance.experimental.instruments

<!-- Insert buttons and diff -->

<table class="tfo-notebook-buttons tfo-api" align="left">
</table>

<a target="_blank" href="https://github.com/google/tf-quant-finance/blob/master/tf_quant_finance/experimental/instruments/__init__.py">View source</a>



Instruments.



## Classes

[`class AverageType`](../../tf_quant_finance/experimental/instruments/AverageType.md): Averaging types.

[`class Bond`](../../tf_quant_finance/experimental/instruments/Bond.md): Represents a batch of fixed coupon bonds.

[`class CMSCashflowStream`](../../tf_quant_finance/experimental/instruments/CMSCashflowStream.md): Represents a batch of cashflows indexed to a CMS rate.

[`class CMSCouponSpecs`](../../tf_quant_finance/experimental/instruments/CMSCouponSpecs.md): CMSCouponSpecs(coupon_frequency, tenor, float_leg, fixed_leg, notional, daycount_convention, coupon_basis, coupon_multiplier, businessday_rule)

[`class CMSSwap`](../../tf_quant_finance/experimental/instruments/CMSSwap.md): Represents a batch of CMS Swaps.

[`class CapAndFloor`](../../tf_quant_finance/experimental/instruments/CapAndFloor.md): Represents a batch of Caps and/or Floors.

[`class DayCountConvention`](../../tf_quant_finance/experimental/instruments/DayCountConvention.md): Day count conventions for accrual.

[`class EurodollarFutures`](../../tf_quant_finance/experimental/instruments/EurodollarFutures.md): Represents a collection of Eurodollar futures contracts.

[`class FixedCashflowStream`](../../tf_quant_finance/experimental/instruments/FixedCashflowStream.md): Represents a batch of fixed stream of cashflows.

[`class FixedCouponSpecs`](../../tf_quant_finance/experimental/instruments/FixedCouponSpecs.md): FixedCouponSpecs(coupon_frequency, currency, notional, coupon_rate, daycount_convention, businessday_rule)

[`class FloatCouponSpecs`](../../tf_quant_finance/experimental/instruments/FloatCouponSpecs.md): FloatCouponSpecs(coupon_frequency, reference_rate_term, reset_frequency, currency, notional, daycount_convention, businessday_rule, coupon_basis, coupon_multiplier)

[`class FloatingCashflowStream`](../../tf_quant_finance/experimental/instruments/FloatingCashflowStream.md): Represents a batch of cashflows indexed to a floating rate.

[`class FloatingRateNote`](../../tf_quant_finance/experimental/instruments/FloatingRateNote.md): Represents a batch of floating rate notes.

[`class ForwardRateAgreement`](../../tf_quant_finance/experimental/instruments/ForwardRateAgreement.md): Represents a batch of Forward Rate Agreements (FRA).

[`class InterestRateMarket`](../../tf_quant_finance/experimental/instruments/InterestRateMarket.md): InterestRateMarket(reference_curve, discount_curve, libor_rate, swap_rate, volatility_curve)

[`class InterestRateModelType`](../../tf_quant_finance/experimental/instruments/InterestRateModelType.md): Models for pricing interest rate derivatives.

[`class InterestRateSwap`](../../tf_quant_finance/experimental/instruments/InterestRateSwap.md): Represents a batch of Interest Rate Swaps (IRS).

[`class OvernightIndexLinkedFutures`](../../tf_quant_finance/experimental/instruments/OvernightIndexLinkedFutures.md): Represents a collection of futures linked to an average of overnight rates.

[`class RateCurve`](../../tf_quant_finance/experimental/instruments/RateCurve.md): Represents an interest rate curve.

[`class Swaption`](../../tf_quant_finance/experimental/instruments/Swaption.md): Represents a batch of European Swaptions.

## Functions

[`ratecurve_from_discounting_function(...)`](../../tf_quant_finance/experimental/instruments/ratecurve_from_discounting_function.md): Returns `RateCurve` object using the supplied function for discounting.

