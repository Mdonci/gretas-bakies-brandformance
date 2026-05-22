# Greta's Bakies product page wireframe

This wireframe defines the reusable product page system for all 10 Greta's Bakies cookie flavors. Each flavor gets its own page, with the same section order and same common copy. Only the hero section changes by flavor.

The structure is mobile first. Desktop can expand sections into columns, but the order below should stay intact on small screens.

## page model

Each product page uses this top-to-bottom order:

1. common: header and navigation
2. common: pickup info bar
3. tailored: flavor hero
4. common: conversion panel
5. common: why Greta's
6. common: how to enjoy
7. common: gifting section
8. common: FAQ accordion
9. common: footer

## global page behavior

### mobile first rules

- Put the hero image first, then the flavor name, then the hero line, then the short description.
- Keep the primary CTA visible after the hero copy. On mobile, use a sticky bottom bar with flavor name, price if available, quantity, and "add to pickup order."
- Use accordions for ingredients, allergens, pickup details, and storage so the page feels clean without hiding purchase-critical information.
- Keep paragraphs short. Most body copy should be one to two sentences.
- Avoid side-by-side modules on mobile. Stack in this order: image, copy, CTA, proof, details.
- Use large tap targets for quantity, flavor add-ons, and pickup date selection.
- Show pickup location language before checkout language. The customer should know this is Irvine pickup before she taps order.
- Do not make customers re-read the same policy in three places. State pickup clearly in the info bar, repeat it in the conversion panel, then answer details in FAQ.

### desktop adaptation

- Hero can become a two-column layout: photography on the left, purchase panel on the right.
- The conversion panel can sit beside the hero copy as a sticky purchase card.
- Common sections can use two-column editorial blocks, but the copy stays the same.
- FAQ remains accordion-style for scannability.

## common section 1: header and navigation

**label:** COMMON  
**appears on:** every product page  
**purpose:** orient, establish brand, help customers move between menu, pickup, and gifting.

### layout

- Top left: Greta's Bakies logo
- Top right mobile: menu icon and cart icon
- Desktop nav: cookies, pickup, gifting, about, cart
- Small byline under logo or in nav area: "thick cookies from Irvine"

### copy

**logo byline:**  
thick cookies from Irvine

**nav labels:**

- cookies
- pickup
- gifting
- about
- cart

**optional cart empty state:**  
Your pouch is empty. Fixable.

**optional cart active state:**  
Cookies for pickup.

### visual notes

- Header should feel quiet, not bakery-cute.
- Use the matte deep berry color as an anchor, with plenty of warm neutral space.
- Keep nav labels lowercase or sentence case.

## common section 2: pickup info bar

**label:** COMMON  
**appears on:** every product page  
**purpose:** make local-only ordering clear before the customer builds a cart.

### layout

- Thin bar below nav
- One line on mobile, expandable if needed
- Link to pickup details or FAQ

### copy

**primary bar:**  
Baked in an Irvine home kitchen. Local pickup only right now.

**expanded line if tapped:**  
Choose your pickup window at checkout. The exact Irvine pickup details are shared after your order is confirmed.

### visual notes

- Do not use urgency language.
- Keep it helpful and plain.
- If a future local delivery option exists, this bar can become: "Irvine pickup today. Local delivery opens when the oven schedule allows." Until then, do not promise delivery.

## tailored section: flavor hero

**label:** TAILORED  
**appears on:** every product page, with flavor-specific copy  
**purpose:** sell the specific cookie through texture, ingredients, personality, pairing, and photography.

### layout

Mobile order:

1. Product photo carousel
2. Flavor name
3. Hero sample line
4. Short description
5. Key ingredients
6. What makes this one different
7. Pairs well with
8. Primary CTA
9. Secondary add-ons
10. Pickup note

Desktop order:

- Left: photo carousel
- Right: flavor name, hero line, description, ingredients, differentiator, pairing, CTA, add-ons, pickup note

### shared CTA copy for all hero sections

**primary CTA:**  
Add to pickup order

**secondary CTA:**  
Build a mixed box

**pickup note under CTA:**  
Pickup is in Irvine. Choose your window at checkout.

**quantity helper:**  
One cookie is a full dessert. Two means you planned ahead.

### approved sample line placement

Use one hero sample line per flavor. Approved lines from the brand bank are used exactly where possible. Matching-tone lines are used for the flavors that did not have an approved owner line.

## tailored hero copy by flavor

### chocolate chip

**label:** TAILORED  
**flavor name:** Chocolate Chip  
**approved line used:** "For people who order chocolate chip to judge the whole place."

**hero line:**  
For people who order chocolate chip to judge the whole place.

**description:**  
A thick 4 oz cookie with a set edge, a soft middle, and chocolate pockets that stay the reason you came here. It is the familiar one, but it still has to earn the first bite.

**key ingredients:**  
Butter, brown sugar, vanilla, eggs, flour, and real chocolate chips folded through the dough.

**what makes this one different:**  
This is the benchmark cookie. No swirl, no fruit, no frosting, just the dough, the chocolate, and whether the middle does what it should.

**pairs well with:**  
Hot coffee, cold milk, or the drive home when you said you would wait.

**visual and photography note:**  
Show one whole cookie with a craggy top and visible chocolate chips, plus one split cookie with melted chocolate pockets in the center. The first image should make the thickness obvious. Include a matte deep berry pouch slightly behind the cookie, not centered.

### triple chocolate

**label:** TAILORED  
**flavor name:** Triple Chocolate  
**approved line used:** "The one for people who meant it when they said dessert."

**hero line:**  
The one for people who meant it when they said dessert.

**description:**  
Dark cocoa dough, chocolate chips, and a middle that goes soft when you warm it for eight seconds. It eats rich without needing a speech about it.

**key ingredients:**  
Cocoa, butter, brown sugar, eggs, flour, chocolate chips, and extra chocolate folded into the dough.

**what makes this one different:**  
It is the deepest cookie on the menu. The texture reads fudgy first, with chocolate in the crumb and chocolate in the bite.

**pairs well with:**  
Black coffee, espresso, or a quiet Friday night where dinner was snacks.

**visual and photography note:**  
Use dramatic contrast. Photograph the split center close enough to show the dense cocoa crumb and melted chocolate. Add a small pile of chocolate pieces in the frame for ingredient proof, but keep the cookie in charge.

### matcha + macadamia

**label:** TAILORED  
**flavor name:** Matcha + Macadamia  
**approved line used:** "For the matcha person in every group chat."

**hero line:**  
For the matcha person in every group chat.

**description:**  
Soft green matcha crumb with buttery macadamia pieces tucked through the middle. The green is matcha, the crunch is macadamia, and the cookie still knows it is dessert.

**key ingredients:**  
Matcha, macadamia nuts, butter, brown sugar, eggs, flour, and vanilla.

**what makes this one different:**  
This is the earthy one. It has a quieter sweetness and a nutty finish, so it feels more grown-up without getting precious.

**pairs well with:**  
Iced matcha, hot green tea, or coffee if you like the bitter with the buttery.

**visual and photography note:**  
The green must look natural and appetizing, not neon. Capture a split cookie so the matcha color carries into the center. Show macadamia pieces on top and inside. Include a small dish of matcha powder only if it looks clean and real.

### red velvet

**label:** TAILORED  
**flavor name:** Red Velvet  
**approved line used:** "The one that looks dramatic and eats soft."

**hero line:**  
The one that looks dramatic and eats soft.

**description:**  
Soft cocoa crumb, a red velvet bite, and cream cheese where it belongs. This is the only cookie on the menu with food coloring, because red velvet has a job to do.

**key ingredients:**  
Cocoa, butter, brown sugar, eggs, flour, vanilla, red food coloring, and cream cheese.

**what makes this one different:**  
It brings the most visual drama, but the bite stays soft and familiar. The cream cheese gives it a little tang against the cocoa dough.

**pairs well with:**  
Hot coffee, black tea, or a birthday where cake feels like too much.

**visual and photography note:**  
Photograph the red crumb clearly, with cream cheese visible on top or in the center depending on final recipe format. Avoid over-saturation. The red should feel like red velvet, not candy. Use a neutral plate so the color does the work.

### biscoff

**label:** TAILORED  
**flavor name:** Biscoff  
**approved line used:** "Sweet and spiced, and very hard to split evenly."

**hero line:**  
Sweet and spiced, and very hard to split evenly.

**description:**  
Cookie butter warmth in a thick cookie with a soft center and a little spiced edge. It is the one that smells like you made a good decision before you even take the first bite.

**key ingredients:**  
Biscoff cookie butter, Biscoff cookie pieces, butter, brown sugar, eggs, flour, and vanilla.

**what makes this one different:**  
It is the most nostalgic flavor on the menu. The spice is gentle, the sweetness is round, and the cookie butter makes the middle feel especially soft.

**pairs well with:**  
Coffee with cream, chai, or an after-dinner plate that everyone keeps reaching toward.

**visual and photography note:**  
Show a visible cookie butter center or ribbon if the recipe includes one. Use crushed Biscoff crumbs around the cookie for immediate flavor recognition. A split shot should show the warm tan interior and any cookie butter softness.

### caramel + pretzel

**label:** TAILORED  
**flavor name:** Caramel + Pretzel  
**approved line used:** "The salty-sweet one people pretend they bought for the table."

**hero line:**  
The salty-sweet one people pretend they bought for the table.

**description:**  
A soft middle with caramel pull and pretzel snap, built for the person who wants salt with the sweet part. The edge holds, the center gives, and the pretzel keeps it from getting too polite.

**key ingredients:**  
Caramel, pretzel pieces, butter, brown sugar, eggs, flour, vanilla, and a little salt.

**what makes this one different:**  
This cookie has the most contrast. Soft and crunchy, sweet and salty, with caramel doing the dramatic part.

**pairs well with:**  
Cold brew, black tea, or a snack dinner that turned into dessert.

**visual and photography note:**  
The caramel pull is the hero. Capture one split shot with caramel stretching between halves. Keep pretzel pieces visible on top so the salt cue is immediate. Add a few broken pretzels in frame, but avoid clutter.

### peanut butter

**label:** TAILORED  
**flavor name:** Peanut Butter  
**matching-tone line used:** "For peanut butter people who want the whole cookie to commit."

**hero line:**  
For peanut butter people who want the whole cookie to commit.

**description:**  
Dense, soft, and unmistakably peanut butter from the first bite. The middle stays rich, the edge sets up, and the flavor shows up early.

**key ingredients:**  
Peanut butter, butter, brown sugar, eggs, flour, vanilla, and roasted peanuts if used in the final recipe.

**what makes this one different:**  
It is the most direct cookie on the menu. No hidden note, no gentle suggestion, just peanut butter doing real work.

**pairs well with:**  
Cold milk, hot coffee, or a square of dark chocolate if you are building a plate.

**visual and photography note:**  
Show the dense interior and any fork mark, peanut piece, or top texture that makes it read peanut butter immediately. Keep the color warm, not gray. Include a small smear of peanut butter on a spoon only if it feels natural.

### apple

**label:** TAILORED  
**flavor name:** Apple  
**approved line referenced:** "The apple cookie tastes like apple instead of candle."

**hero line:**  
The apple cookie tastes like apple instead of candle.

**description:**  
Soft middle, real apple pieces, and cinnamon that knows when to stop. It is cozy without turning into a scented candle, which is harder than it sounds.

**key ingredients:**  
Apple pieces, cinnamon, butter, brown sugar, eggs, flour, vanilla, and a little salt.

**what makes this one different:**  
This is the cozy one. It has fruit, spice, and a softer bakery feeling, but it still eats like a thick cookie.

**pairs well with:**  
Black tea, coffee, or the night you want tea and one very serious cookie.

**visual and photography note:**  
Show apple pieces in the split center so the flavor feels real. Use a warm neutral background and one fresh apple wedge nearby. Avoid fall-prop overload. The cookie should not look seasonal-only unless the business chooses that later.

### almond

**label:** TAILORED  
**flavor name:** Almond  
**matching-tone line used:** "The almond slices make it feel a little dressed up."

**hero line:**  
The almond slices make it feel a little dressed up.

**description:**  
A soft, thick cookie with almond in the bite and a little crunch on top. It is quiet, nutty, and very good with coffee.

**key ingredients:**  
Almonds, almond extract if used, butter, brown sugar, eggs, flour, vanilla, and sliced almonds on top.

**what makes this one different:**  
It is the most restrained cookie in the lineup. Less dramatic than the chocolate ones, more polished than the cozy ones, and still fully a cookie.

**pairs well with:**  
Hot coffee, cappuccino, or afternoon tea when you want the cookie to feel a little grown up.

**visual and photography note:**  
Top texture matters here. Photograph sliced almonds clearly on the surface, with a split shot that shows the soft inside under the crunch. Use the deep berry pouch in frame because almond benefits from a more polished setting.

### raspberry

**label:** TAILORED  
**flavor name:** Raspberry  
**approved line used:** "A fruit cookie for people who still want a cookie."

**hero line:**  
A fruit cookie for people who still want a cookie.

**description:**  
Jammy raspberry through a soft middle, with enough tartness to keep the cookie awake. The pink is raspberry, and the cookie is still thick enough to make you pause before sharing.

**key ingredients:**  
Raspberry, butter, brown sugar, eggs, flour, vanilla, and white chocolate if used in the final recipe.

**what makes this one different:**  
It is the brightest cookie on the menu. Fruit leads the flavor, but the texture stays dense and buttery instead of turning cakey.

**pairs well with:**  
Black tea, iced coffee, or a gift box for the friend who says she is fine.

**visual and photography note:**  
The raspberry color needs to be visible in the center or swirl. Photograph a split cookie with jammy pockets or berry pieces showing. Keep the pink natural. A small dish of raspberries can sit nearby, but the cookie should carry the color on its own.

## common section 4: conversion panel

**label:** COMMON  
**appears on:** every product page  
**purpose:** make ordering feel simple, local, and gift-ready.

### layout

Mobile:

- Sticky bottom CTA after customer scrolls past hero
- Quantity selector
- Pickup date or window selector
- Add-ons module
- Trust note

Desktop:

- Sticky card on the right side of hero or immediately below hero copy

### copy

**panel heading:**  
Ready for pickup in Irvine

**body copy:**  
Choose your flavor, pick your quantity, and select a pickup window at checkout. Greta bakes from a home kitchen in Irvine, so the oven schedule is real and the pickup plan matters.

**primary CTA:**  
Add to pickup order

**secondary CTA:**  
Build a mixed box

**quantity note:**  
One 4 oz cookie is a full dessert. Four makes it look like you planned dessert for everyone.

**pickup selector helper:**  
Pickup windows are based on the bake schedule. Choose the one that fits your day.

**gift checkbox:**  
Make it a gift

**gift helper copy:**  
Packed in the matte deep berry pouch, ready to hand over as is.

**add-ons:**

- Add another flavor
- Build a six-cookie mixed box
- Add a handwritten pickup note if operationally possible
- Add a warming card for gifting

**trust note:**  
Made in an Irvine home kitchen under a California Cottage Food Act Class A permit.

### conversion notes

- Do not bury pickup requirements under the CTA.
- If inventory is limited, say "sold out for this bake" instead of creating fake urgency.
- If pickup windows are full, offer "join the next bake list" or "see other flavors."
- If a flavor sells out, keep the product page live for SEO and email capture.

### empty, sold out, and waitlist states

**sold out state:**  
Sold out for this bake.

**sold out helper:**  
Greta bakes around pickup windows, not a warehouse shelf. Join the next bake list and we will tell you when this one is back.

**waitlist CTA:**  
Tell me when it is back

**inventory low state:**  
A few left for this pickup window.

**cart reminder:**  
Pickup is in Irvine. Details come with your confirmation.

## common section 5: why Greta's

**label:** COMMON  
**appears on:** every product page  
**purpose:** build trust without over-explaining.

### layout

- Section heading
- Three proof cards
- Short kitchen note
- Optional owner photo or kitchen detail photo

### copy

**heading:**  
Why Greta's

**intro:**  
Greta's Bakies is one woman, one oven, and ten thick cookies from a home kitchen in Irvine. The cookies are 4 oz, the middles stay soft, and the pickup plan is local on purpose.

**proof card 1 heading:**  
Made in Irvine

**proof card 1 copy:**  
Baked from a home kitchen in Irvine under a California Cottage Food Act Class A permit. Local pickup only, so the cookies do not have to pretend they were built for a shipping truck.

**proof card 2 heading:**  
Ingredients you can read

**proof card 2 copy:**  
Butter, sugar, eggs, flour, chocolate, matcha, raspberry, apple, almonds, peanuts, pretzels, caramel. The flavor should show up as the thing it says it is.

**proof card 3 heading:**  
The middle is the point

**proof card 3 copy:**  
Each cookie is thick enough to hold a soft center. Warm it for eight seconds if you want the middle to relax a little.

**kitchen note:**  
Made in an Irvine kitchen with a very serious oven schedule.

**approved sample line placement:**  
Use "Made in an Irvine kitchen with a very serious oven schedule." as the closing kitchen note in this section.

### visual notes

- Use a real kitchen detail if available: trays, cooling rack, hands packing pouches.
- Do not over-stage the home kitchen. The proof is the specific detail, not a fake lifestyle scene.

## common section 6: how to enjoy

**label:** COMMON  
**appears on:** every product page  
**purpose:** improve the eating experience and reduce post-purchase questions.

### layout

- Section heading
- Three instruction cards: warm, store, pair
- Small note for gifting

### copy

**heading:**  
How to enjoy

**intro:**  
The cookie is ready as is. If you like the middle softer, give it eight seconds and pay attention.

**card 1 heading:**  
Warm it

**card 1 copy:**  
Microwave for about eight seconds. You want the center soft and the edge still holding.

**card 2 heading:**  
Store it

**card 2 copy:**  
Keep cookies sealed at room temperature and eat within the week, ideally sooner. If you freeze them, wrap them well and warm gently after thawing.

**card 3 heading:**  
Pair it

**card 3 copy:**  
Coffee works. Tea works. Standing in the kitchen before anyone else notices also works.

**gift note:**  
If you are bringing them somewhere, keep them in the pouch until you arrive. Put them on a plate and take the compliment.

**approved sample line placement:**  
Use "If you warm it for eight seconds, you will understand." as social or product-card microcopy that links into this section.

### visual notes

- Show a split cookie after warming, not a messy melted pile.
- If using video, show the hand break or center pull in under five seconds.

## common section 7: gifting section

**label:** COMMON  
**appears on:** every product page  
**purpose:** turn a single product page into a host gift and group order opportunity.

### layout

- Large image of matte deep berry pouch
- Gift copy
- CTA to build mixed box
- Short occasion list

### copy

**heading:**  
Bring these when you said you would handle dessert

**body:**  
The pouch is matte deep berry, so it already looks like you thought about it. Bring one for a friend, four for the table, or a mixed box when nobody in the group chat can agree.

**occasion list heading:**  
Good for

**occasion bullets:**

- Friday night, when dinner was snacks
- Newport birthdays and Costa Mesa Fridays
- The friend who says she is fine
- The dinner party you remembered at lunch
- The thank-you that needs to taste like you meant it

**CTA:**  
Build a giftable box

**secondary line:**  
The pouch does the wrapping for you.

**approved sample line placement:**  
Use "Bring these when you said you would handle dessert." as the gifting section heading. Use "For Friday night, when dinner was snacks." in the occasion list.

### visual notes

- Hero the matte deep berry pouch in natural light.
- Show pouch in hand for scale.
- Include one shot of cookies plated after being removed from the pouch.
- Keep gift styling practical: plate, napkin, coffee cup, passenger seat, or host counter.

## common section 8: FAQ accordion

**label:** COMMON  
**appears on:** every product page  
**purpose:** answer purchase blockers without making the page feel legal.

### layout

- Accordion list
- Keep answers short
- Place near bottom after desire and conversion sections

### copy

**heading:**  
Questions before pickup

**FAQ 1 question:**  
How do I order?

**FAQ 1 answer:**  
Choose your cookies, add them to your pickup order, and select a pickup window at checkout. You will get the Irvine pickup details after your order is confirmed.

**FAQ 2 question:**  
Do you deliver?

**FAQ 2 answer:**  
Not right now. Greta's Bakies is direct-to-consumer with local pickup in Irvine.

**FAQ 3 question:**  
Where are the cookies made?

**FAQ 3 answer:**  
They are made in a home kitchen in Irvine under a California Cottage Food Act Class A permit.

**FAQ 4 question:**  
How big is each cookie?

**FAQ 4 answer:**  
Each cookie is 4 oz and thick enough to hold a soft middle. One cookie is a real dessert.

**FAQ 5 question:**  
How should I store them?

**FAQ 5 answer:**  
Keep them sealed at room temperature and eat within the week, ideally sooner. Warm for about eight seconds if you want the middle softer.

**FAQ 6 question:**  
Do the cookies contain allergens?

**FAQ 6 answer:**  
Yes. Cookies may contain wheat, eggs, milk, tree nuts, peanuts, and soy depending on the flavor. They are made in a home kitchen that handles common allergens. Check the flavor details before ordering.

**FAQ 7 question:**  
Are the ingredients listed?

**FAQ 7 answer:**  
Yes. Each flavor page lists the key ingredients, and final labels should include the full ingredient and allergen information required for cottage food sales.

**FAQ 8 question:**  
Is there food coloring?

**FAQ 8 answer:**  
Red Velvet uses food coloring because red velvet should be red. The green in Matcha + Macadamia is matcha, and the pink in Raspberry is raspberry.

**FAQ 9 question:**  
Can I order for a gift?

**FAQ 9 answer:**  
Yes. Choose "make it a gift" at checkout if available. The cookies come in the matte deep berry pouch, which is ready to hand over as is.

**FAQ 10 question:**  
Can I mix flavors?

**FAQ 10 answer:**  
Yes. Build a mixed box if you want a little chocolate, a little fruit, and one cookie you keep for yourself.

### compliance note

- Final site copy should be reviewed against current California Cottage Food Act Class A labeling and disclosure requirements before launch.
- Do not imply inspection status beyond the permit category unless confirmed.

## common section 9: footer

**label:** COMMON  
**appears on:** every product page  
**purpose:** close with local proof, helpful links, and compliance basics.

### layout

- Logo and byline
- Footer nav
- Contact or Instagram link
- Cottage food note
- Pickup location note

### copy

**byline:**  
Thick cookies from Irvine, finally.

**footer note:**  
Greta's Bakies is a home kitchen cookie business in Irvine, California. Local pickup only.

**cottage food line:**  
Made under a California Cottage Food Act Class A permit.

**footer nav labels:**

- cookies
- pickup details
- gifting
- ingredients and allergens
- Instagram
- contact

**microcopy:**  
Your friend in Newport is going to ask where these came from.

**approved sample line placement:**  
Use "Thick cookies from Irvine, finally." as the footer byline. Use "Your friend in Newport is going to ask where these came from." as rotating footer microcopy or confirmation-page copy.

## photography requirements

### global photography system

Every flavor page needs these assets:

1. Whole cookie hero on a simple surface
2. Split cookie showing the middle
3. Close-up texture shot
4. Cookie next to matte deep berry pouch
5. In-hand scale shot or plate scale shot
6. Optional short video of the split or warm center

### global visual rules

- Show thickness clearly. The 4 oz size should be obvious without needing a ruler.
- Lead with texture. The middle matters more than the prop.
- Keep backgrounds warm, clean, and real.
- Use the deep berry pouch as a brand anchor, not a constant center-stage object.
- Avoid fake bakery props, too many flowers, and anything that makes the cookies look mass-produced.
- Shoot natural light whenever possible.
- Keep ingredient props minimal and specific: matcha powder, raspberries, pretzels, almonds, apple, chocolate, peanuts.
- Every flavor needs at least one image where the customer can identify the flavor without reading.

### flavor-specific shot checklist

| flavor | must show | avoid |
|---|---|---|
| Chocolate Chip | melted chocolate pockets, thick split center | making it look flat or generic |
| Triple Chocolate | dark cocoa crumb, melted chocolate, fudgy center | over-dark images where texture disappears |
| Matcha + Macadamia | natural green crumb, macadamia pieces | neon green color correction |
| Red Velvet | red crumb, cream cheese, soft texture | candy-red saturation |
| Biscoff | cookie butter center or ribbon, Biscoff crumb | too many loose crumbs covering the cookie |
| Caramel + Pretzel | caramel pull, pretzel pieces, salt cue | caramel mess that hides the cookie structure |
| Peanut Butter | dense center, peanut butter top texture | dry-looking crumb |
| Apple | real apple pieces, cinnamon warmth | fall prop overload |
| Almond | sliced almond top, soft interior | making it look like a breakfast pastry |
| Raspberry | jammy raspberry pockets, natural pink | artificial-looking pink |

## conversion elements across every flavor page

### primary conversion goal

Get the customer to add the flavor to a local pickup order.

### secondary conversion goals

- Build a mixed box
- Add more flavors to the cart
- Make the order gift-ready
- Join the next bake list if sold out
- Understand pickup before checkout

### required conversion components

- Primary CTA: "Add to pickup order"
- Secondary CTA: "Build a mixed box"
- Sticky mobile CTA after hero scroll
- Quantity selector
- Pickup window selector or prompt
- Gift checkbox
- Add another flavor carousel
- Sold out state with waitlist CTA
- Trust note near CTA: "Made in an Irvine home kitchen under a California Cottage Food Act Class A permit."
- Pickup note near CTA: "Pickup is in Irvine. Choose your window at checkout."

### suggested add-on module copy

**heading:**  
Make it a box

**body:**  
Add a few flavors and call dessert handled. Chocolate for the person who asks first, fruit for the one who says she only wants a bite, and one extra because someone always changes their mind.

**add-on CTA:**  
Add another flavor

**gift CTA:**  
Make it a gift

## approved sample line map

| approved line | recommended placement |
|---|---|
| For the gooey-middle cookie people. | Sitewide product card or collection page intro |
| This is so good, you can tell nobody tried to make it behave. | Rotating product page microcopy or cart confirmation |
| Thick enough to make you pause before sharing. | Raspberry hero description and general texture module |
| If you warm it for eight seconds, you will understand. | How to enjoy section and order confirmation |
| Bring these when you said you would handle dessert. | Gifting section heading |
| Thick cookies from Irvine, finally. | Footer byline or collection page hero |
| Made in an Irvine kitchen with a very serious oven schedule. | Why Greta's section kitchen note |
| Your friend in Newport is going to ask where these came from. | Footer microcopy or gifting module |
| For Friday night, when dinner was snacks. | Gifting occasion list and Triple Chocolate pairing |
| For people who order chocolate chip to judge the whole place. | Chocolate Chip hero line |
| The one for people who meant it when they said dessert. | Triple Chocolate hero line |
| For the matcha person in every group chat. | Matcha + Macadamia hero line |
| The one that looks dramatic and eats soft. | Red Velvet hero line |
| Sweet and spiced, and very hard to split evenly. | Biscoff hero line |
| The salty-sweet one people pretend they bought for the table. | Caramel + Pretzel hero line |
| A fruit cookie for people who still want a cookie. | Raspberry hero line |

## implementation notes

- Each product page should use the same common section copy unless operations change.
- Flavor pages should not repeat full FAQ answers in the hero. Keep the hero sensory and let FAQ handle logistics.
- Use sentence case for headings.
- Do not use em dashes.
- Do not use wellness claims or guilt language.
- Do not use "artisan," "handcrafted," "premium," "ultimate," or "made with love."
- Final ingredient lists and allergen statements must be confirmed against the actual recipe and legal label before publishing.
