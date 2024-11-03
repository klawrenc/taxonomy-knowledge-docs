      Sales FAQ: OpenShift Subscriptions for AI Accelerators

Internal FAQ \| Subscription updates for OpenShift and OpenShift AI
Hybrid Platforms Product Marketing \| Last updated: September 2024 Table
of Contents ▸ What is the new requirement for OpenShift and OpenShift AI
subscriptions to cover GPUs and other AI accelerators? ▸ Doesn’t RHEL AI
also charge based on AI Accelerators? ▸ What is an accelerator? Why are
they important? ▸ Why is Red Hat making this change? ▸ Is this a price
increase? Who is affected by this change? ▸ What OpenShift platforms and
footprints are impacted by this change? ▸ What is the rationale for
excluding OpenShift Cloud Services from this pricing change? ▸ What
discount is available in Q4 CY24? ▸ Can I mix and match product
subscriptions on the same cluster, such as OpenShift Platform Plus for
the CPUs, and OpenShift Container Platform for the accelerators? ▸ How
is my customer supposed to identify accelerators? What types of
accelerators are counted? ▸ Are all accelerators counted? ▸ At what
product levels across RHEL AI, OpenShift, and OpenShift AI do customers
need to pay for AI accelerators? ▸ If customers have to pay for AI
accelerators in OpenShift and in OpenShift AI, isn’t that double
counting them? ▸ Will Red Hat provide any tools to run on systems to
count accelerators? ▸ What if my customer is not using large language
models (LLMs)? Does this still apply? ▸ Does this change impact the
technical workstation or VDI use cases? ▸ How does this change impact
DPU use cases? Question: What is the new requirement for OpenShift and
OpenShift AI subscriptions to cover GPUs and other AI accelerators?
Confidential: Red Hat associate and NDA partner use only. No further
distribution.

Answer: Currently, self-managed OpenShift and OpenShift AI compute nodes
require subscriptions for all CPU cores in those nodes. Starting on
October 1, 2024, AI accelerators installed in compute nodes and used to
provide compute capacity for AI or other compute workloads (as defined
below) will also require subscriptions for self-managed OpenShift and
OpenShift AI on all supported footprints, including on premises and
public cloud installations An AI Accelerator subscription will cover two
AI accelerator devices. Question: Doesn’t RHEL AI also charge based on
AI Accelerators? Answer: Yes. RHEL AI’s subscription unit of measure is
based on AI accelerators. In general, it is easier for people to
understand why and its use cases because the sole purpose of the RHEL AI
offering is to offer better experiences for people explicitly using
accelerators with large language models (LLMs) . Also, RHEL AI is
included in OpenShift AI. So this document is focused more on OpenShift
and OpenShift AI where more clarity might be needed. Question: What is
an accelerator? Why are they important? Answer: In recent years,
specific hardware technologies have come onto the market that enable
certain compute workloads to perform much faster. These types of
hardware devices are collectively referred to as accelerators or “AI
accelerators” in some Red Hat content. There are several types of
hardware devices available for modern servers that can be classified as
accelerators, including but not limited to GPUs, TPUs, ASICs, and NPUs
(see “What types of accelerators are counted?”). Question: Why is Red
Hat making this change? Answer: Red Hat is updating its subscription
model to continue to align with how it has always charged customers
based on computational power. Red Hat has developed, innovated, and
continued to support these new computing paradigms and accelerated
computing devices. This is a significant investment for Red Hat. As
customers also derive significant value from the use of these
accelerated computing devices, Red Hat believes that customers are
receiving significant value for the cost of the subscription that covers
the accelerators. These subscriptions help Red Hat continue to sustain
these innovations. For a specific list of enhancements and innovations
that Red Hat has driven, please see this deck. Question: Is this a price
increase? Who is affected by this change? Answer: Yes. Existing
OpenShift self-managed and OpenShift AI customers who are already using
accelerators for computational-type workloads will be affected by this
change when they add new subscriptions or renew existing subscriptions.
There is a discount program in place for Q4 CY24 for new deals and
renewals that can only be applied to one year deals. In CY25, the Q4
CY24 discounting program will end. Question: What OpenShift platforms
and footprints are impacted by this change? Answer: All OpenShift
self-managed subscriptions (OpenShift Kubernetes Engine, OpenShift
Container Platform, and OpenShift Platform Plus) on all supported
platforms must now include AI Confidential: Red Hat associate and NDA
partner use only. No further distribution.

Accelerator subscriptions for new subscriptions or on renewal of
existing subscriptions. OpenShift Cloud Services (ARO, ROSA, OSD and
RHOIC) are not impacted at this time. Question: What is the rationale
for excluding OpenShift Cloud Services from this pricing change?
OpenShift Cloud Services, unlike self-managed OpenShift, are priced
based on dynamic usage in the relevant cloud service. These services are
also billed through the cloud provider, so any changes must be planned
and executed in conjunction with the provider. Question: What discount
is available in Q4 CY24? Answer: Red Hat sellers can offer a one-time
discount of up to 100% of the cost of the subscriptions specifically for
the AI accelerators during one year deals. The discount is applicable
only to the quantity of subscriptions needed to entitle AI accelerators
being used for computational workloads in OpenShift and OpenShift AI.
This promotion will use standard commercial deal structuring rules and
NAT tables, and can be applied to any deals closing in Q4 CY24. The
discount will appear as a separate line item on the order form, similar
to other one-time discounts offered in the past (for details, see the
promotion business rules). Question: Can I mix and match product
subscriptions on the same cluster, such as OpenShift Platform Plus for
the CPUs, and OpenShift Container Platform for the accelerators? Answer:
No. This was never an option with x86 subscriptions, and it is not an
option with AI accelerator subscriptions. OpenShift subscriptions must
be for the same product and support level at the cluster level.
Question: How is my customer supposed to identify accelerators? What
types of accelerators are counted? Answer: There are several types of
accelerators that can be used for computing purposes. This chart
provides an up-to-date list of accelerator types as well as which ones
could run compute workload. Once you know the accelerator type, you will
count the accelerator at the card, board, or device level. We charge
based on the “physical” accelerator. This is almost always the unit
quantity the customer purchased from the accelerator vendor. For
example, in a server whose vendor says it has “8 GPUs,” this almost
always means 8 physical accelerator units. To make it easier to quote
the sales order, we use the existing workload SKU (which today is x86
core based) and updated it to represent both x86 cores and accelerator
cards. Question: Are all accelerators counted? Answer: Accelerators are
only counted when they are used to execute a compute workload. A
workload is considered a compute workload when the primary purpose of
the workload is NOT actively drawing pixels on a user’s screen in near
real-time or moving data across a network. This distinction is important
because VFX (visual effects) and streaming applications may use GPUs and
other accelerator hardware, but the primary purpose in these cases is
drawing pixels on a screen. Confidential: Red Hat associate and NDA
partner use only. No further distribution.

In some cases the primary function is moving data across a network,
which also is not considered compute. Examples of compute workloads
include: ● Traditional software applications (Java, Python, Perl, etc.)
● LLMs or other compute-intensive software ● Data science model
training/tuning ● Scientific modeling and physical simulation (protein
folding, fluid dynamics, etc) Question: At what product levels across
RHEL AI, OpenShift, and OpenShift AI do customers need to pay for AI
accelerators? Answer: If you use RHEL AI by itself without OpenShift AI,
then you will need to purchase RHEL AI subscriptions that are based on
AI accelerators. If however you buy OpenShift AI, it includes RHEL AI
and so you would only need to pay for the AI accelerators used in
OpenShift AI and not RHEL AI. OpenShift AI is an addon to OpenShift.
OpenShift AI has never included OpenShift. Customers have always paid
for OpenShift and then paid for the OpenShift AI addon. This will
continue to be the case for AI accelerators. Customers will pay for AI
accelerators in OpenShift AI and AI accelerators in OpenShift. This is
consistent with how they pay for x86 cores in both products. Question:
If customers have to pay for AI accelerators in OpenShift and in
OpenShift AI, isn’t that double counting them? Answer: No. In the same
manner, we are not double counting x86 cores when you purchase OpenShift
and then purchase the OpenShift AI addon. OpenShift AI has drastically
different features than OpenShift. OpenShift AI offers a data scientist
end user experience for model development that includes model training,
tuning, serving, and monitoring model API endpoints, all while allowing
for a sophisticated MLOps pipeline. All of these features leverage
computational resources from AI accelerators. OpenShift AI charges for
AI accelerators to cover the value all those features and more bring to
the customer. Separately, OpenShift is an application platform for
distributed systems. Customers could be using it to broadcast these
workloads in intelligent ways across the AI accelerators. In the same
way OpenShift charges for workloads via each worker node in x86, it
holds the same value for AI accelerators. OpenShift charges for AI
accelerators to cover the value of all those features. Question: Will
Red Hat provide any tools to run on systems to count accelerators?
Answer: AI accelerator subscriptions are based on the honor system.
Since we only require subscriptions for accelerator cards in their
entirety when they are being used with OpenShift or OpenShift AI, it is
difficult to identify the correct count form the operating system. Red
Hat is investigating how this can be changed in the future. See “Are all
accelerators counted?” Question: What if my customer is not using large
language models (LLMs)? Does this still apply? Confidential: Red Hat
associate and NDA partner use only. No further distribution.

Answer: While the SKU has the term “AI accelerator,” any workload that
is classified as compute and run on an accelerator requires entitlement
coverage with a subscription. See “Are all accelerators counted?”
Question: Does this change impact the technical workstation or VDI use
cases? Answer: We do not count GPUs used for the technical workstation
or VDI use case where the GPU is simply used for the purposes of
providing hardware accelerated graphics to the desktop (see “Are all
accelerators counted?”). However, if the accelerator provided to the
virtual desktop environment is in turn used for a compute workload, it
should be counted and covered with a subscription. Question: How does
this change impact DPU use cases? Answer: Today, DPUs have both compute
and networking capabilities. If a DPU is being used for a compute
workload, it needs subscription coverage. If a DPU is being used for
network capabilities only, it does not need subscription coverage. See
this chart. Resources ▸ OneStop ▸ Internal enablement deck ▸ Customer
deck ▸ Questions: hybridplatforms-marketing@redhat.com Confidential: Red
Hat associate and NDA partner use only. No further distribution.
