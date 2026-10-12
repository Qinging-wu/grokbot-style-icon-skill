# Iterating on user feedback

Treat each user correction as a scoped change request.

1. Identify the exact property the user says is wrong or wants adjusted.
2. Separate that property from aspects the user approved. Phrases like “其余不错” or “其他地方很好” mean preserve those other parts.
3. Make the smallest prompt or image change that addresses the correction. Do not restart character analysis or change unrelated color, framing, hairstyle, or clothing.
4. If the requested correction conflicts with a generic rule, follow the user’s correction for this image and retain unrelated rules.
5. Regenerate or edit with the previous result as a style/composition reference only when useful. Keep the original character reference as the source of identity.
6. Briefly report what changed and show the updated image when a generation tool is available.

For recurring corrections that reveal a general failure mode, update the style specification and final visual check. Keep one-off character-specific traits in that character’s prompt only; do not turn an individual hair clip, complexion, pose, or costume into a universal rule.
