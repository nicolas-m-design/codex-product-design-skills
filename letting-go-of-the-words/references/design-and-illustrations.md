# Design and illustrations

Book basis: chapters 3 and 13, with list/table and heading design from chapters 9 and 11. Contents: content and design together; readable presentation; illustration purpose; media accessibility. Modern adaptations are identified below and in the sources reference.

## Design with the words present

Content and presentation determine each other. Bring representative content into early layouts rather than approving empty boxes or placeholder text. Check actual headings, description lengths, long labels, number of levels, and media requirements. Agree how these behave across screen sizes and content types.

When the assignment is copy-only, use the existing design constraints and identify a constraint that makes the content unusable; do not silently redesign the product. Preserve established brand colors and typography unless the task includes changing them or a specific issue requires attention.

## Make information easy to see and follow

- Use a consistent alignment system and predictable placement of recurring controls. Visual clutter can come from competing starting edges, not simply from having many words.
- Preserve space between meaningful chunks. Internal spacing helps readers understand groups; removing it to squeeze in more copy makes scanning harder.
- Keep headings closer to their following content than to the preceding section. Keep a list introduction connected to its list. Avoid large gaps or rules that falsely suggest the page has ended.
- Align sustained prose consistently with its reading direction. Centering long text removes a stable starting edge. A short display heading is a contextual design choice, not automatically a defect.
- Use a legible typeface and size for the intended readers. Do not shrink essential text merely to fit excessive copy. Very long lines tire the eye; extremely short lines break meaningful phrases. Test the actual layout rather than enforcing the book’s suggested character counts.
- Avoid long blocks of capitals or italics. Use visual hierarchy deliberately. Keep underlining and other link signals unambiguous.
- Separate text clearly from busy backgrounds. Maintain usable contrast and never make color the only source of meaning. Do not assume a color has the same cultural meaning everywhere.
- Allow content and controls to remain usable when text is enlarged. Include navigation and secondary content, not just the article body. Avoid clipped controls or lost instructions.
- Evaluate on relevant devices, with keyboard navigation and assistive technology where appropriate. Automated checks and simulations do not establish complete accessibility.

Modern adaptation: the book’s categorical preferences for sans serif fonts, light backgrounds, and site-specific text-size widgets reflect its era and context. Preserve readable, flexible presentation without overriding a tested design system or claiming those choices are universally required. Coordinate with any applicable typography or design guidance rather than duplicating it.

## Choose a visual by the question it answers

| Purpose | Useful choice | Question to answer before producing it |
| --- | --- | --- |
| Show the actual product | Accurate views, scale, interior, use context | What can the buyer not judge from the description? |
| Support self-service | Seat map, location diagram, form annotation | What must the person locate or select? |
| Explain a process | Steps, diagram, controlled demonstration | What sequence or change is hard to understand in words? |
| Explain data | Comparison chart, map, table | What relationship or finding should the reader see? |
| Establish mood or identity | Relevant people, environment, brand imagery | What message will the intended audience take from it? |

An illustration can replace words, support them, or introduce a misleading message. Specify its job before choosing it. If a form repeatedly needs a diagram to explain a hard-to-find code, consider whether the underlying document can be improved too; propose that only within scope.

### Keep the image useful in context

Make the subject and relevance clear. A thumbnail must still be recognizable at its displayed size. Avoid large imagery that hides the primary task or buries important information. Test the whole page, since surrounding copy changes how an image is interpreted.

People in photographs communicate who belongs. Show appropriate diversity truthfully; do not imply a workforce, customer population, endorsement, or event that the image does not represent. Ask what viewers think a picture is saying rather than only whether they like it. A serious expression can convey expertise in one setting and distress in another.

Do not make essential navigation resemble unrelated advertisements. Do not rely on eye-catching decoration to carry information people are trying to find. Motion should explain or meaningfully support the content, with appropriate user control; avoid moving text that readers must chase.

For process animation, let people follow steps at their own pace. For video, provide a descriptive title and a clear purpose, use a length suited to the task, and account for loading costs. The book’s specific video durations and file-size targets are historical examples, not current requirements.

### Show data honestly

Use a chart or table when it makes comparison easier than prose. Put a supported takeaway in the title when appropriate. Include units, period, labels, and necessary source context. Ensure scales, selections, and encodings do not exaggerate differences.

The book emphasizes zero baselines. Apply that carefully: bars encode values by length and normally need zero; other chart types can require a different scale to reveal meaningful variation. Make any nonzero baseline clear and choose it for the analytical task, not drama. Do not claim a trend from a single time point or causality from a comparison.

Allow useful layers or filters for dense maps and data when the task warrants them, but keep the core explanation available and preserve context when selections change.

## Provide equivalent information

These are modern implementation adaptations of the book’s accessibility principle:

- For an informative image, describe the information it contributes in context, not merely its visual existence.
- For a purely decorative image or redundant image inside a text link, use an empty text alternative where appropriate. Do not narrate decorative imagery simply because the book describes alt text for mood pictures. [W3C decorative-image guidance](https://www.w3.org/WAI/tutorials/images/decorative/).
- For a chart or diagram, provide a concise identification plus an accessible longer explanation or data equivalent containing the important values, relationships, and trends. Do not cram an entire table into one enormous alt attribute. [W3C complex-image guidance](https://www.w3.org/WAI/tutorials/images/complex/).
- For a functional image, ensure the control’s accessible name communicates its action or destination. For maps with selectable areas, offer an equivalent usable way to select; a prose description alone does not reproduce the interaction.
- For audio and video, account for captions, transcripts, and visual information absent from the audio. Choose the needed equivalents for the actual media rather than asserting a transcript alone makes all video accessible. [W3C media guidance](https://www.w3.org/WAI/media/av/).
- For optional show/hide details, use an operable control and expose its expanded state. Keyboard activation and coherent reading order matter. [W3C disclosure pattern](https://www.w3.org/WAI/ARIA/apg/patterns/disclosure/).

A useful editorial check is to imagine explaining the page to someone who cannot see it. What would they need to know or do? This exposes missing information; it does not replace implementation testing.
