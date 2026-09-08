# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
CRITICAL MANDATORY: Ling wears SOLID LAVENDER LIGHT PURPLE flat fill on short-sleeve T-shirt, color approximately #C69BC8. Purple shirt must be clearly visible on torso. NOT white shirt, NOT gray shirt, NOT cream shirt, NOT all-black-and-white outfit.

Generate one standalone 16:9 horizontal Chinese knowledge-explainer illustration.

Input references:
Use the three mandatory references supplied by the three-anchor lock. Image 1 is the authoritative Ling identity anchor, Image 2 is the authoritative expression-and-action anchor, and Image 3 is the authoritative color, brightness, and overall-feeling anchor. Identity comes from Images 1-2; color treatment comes from Image 3. Any previous frame or composition reference must preserve both.

Visual DNA:
Use a solid #F5F5F7 background (RGB 245, 245, 247) uniformly across the entire canvas. Minimalist black hand-drawn line art with medium, slightly wobbly rounded strokes. A funny hand-drawn educational cartoon feeling: simple, clean, expressive, and easy to understand at a glance. Center the visual group as a whole. Keep all essential characters, props, arrows, and labels inside the middle roughly 80% of the canvas width, leaving about 8%-12% clean #F5F5F7 negative space on both the left and right and about 6%-10% breathing room on the top and bottom. Nothing important may touch or be cropped by an edge. Use at most one main accent color and one optional secondary accent: mustard yellow, burnt orange, muted teal/blue, or red. Keep the background as that exact solid flat color, with no gradients, shadows, paper texture, complex background, commercial vector style, PPT infographic look, meme collage, childish mascot poster, or realistic UI.
The flat-background and flat-scene restrictions do not flatten Ling’s own coloring. Preserve Image 3’s restrained natural tonal variation on Ling’s face, shirt, hair, and glasses.

Recurring original IP character required:
Ling is the fixed recurring protagonist and core IP of this illustration series, never an anonymous or replaceable cartoon figure. Match the same person shown in Images 1-2, not merely a similar style: an adult female cartoon character with a soft rounded face, warm skin, a very large head and tiny body, long straight black hair parted in the middle and falling past the shoulders, the same silhouette and hairline, thin curved eyebrows, the same eye shape and placement, small manga-like nose and restrained mouth, thin silver round-frame glasses with the same structure, a light lavender short-sleeved T-shirt, thin black line arms and legs, simple round black hands and feet, and a white sticker-like outer border. Keep the face geometry, five-feature placement, hair, glasses, default clothing, skin tone, and head-to-body ratio consistent across the whole image set. Match Image 3’s color values, brightness, saturation, fill texture, shadow strength, and overall light feeling. Use its clean, slightly pale, even hand-painted fills with restrained natural tonal variation: skin centered around #FBB981, T-shirt centered around #C69BC8, deep neutral-black hair and thin silver glasses, black linework, and white eyes/sticker border. Ling must perform or experience the core conceptual action, not decorate the scene. Her personality is gentle, intelligent, and “gentle-yet-smart”: the action may be overly literal or awkward, while the observation and knowledge remain intelligent and accurate. Use one clear main Ling by default. When other people are necessary, make them secondary and visually distinct.

Fixed limb skeleton:
Match the limb construction in Image 2 exactly. Ling has two arms and two legs unless one is explicitly cropped or occluded. Each arm is one continuous, uniform thin black hand-drawn line emerging from the side of the small lavender torso and ending in a small solid black circular or oval hand. Each leg is one continuous, uniform thin black hand-drawn line emerging from the bottom of the torso and ending in a slightly larger solid black oval foot. Bending, pointing, holding, lifting, and walking change only the direction of these single black lines and their contact with props. Keep the limbs thinner than the torso outline. No lavender sleeve-shaped arms, skin-colored arms, palms, fingers, thumbs, wrists, double-line cartoon limbs, anatomical limb volume, pants legs, knees, calves, shoes, broken attachments, extra limbs, or missing visible limbs.

Expression continuity ledger:
Previous shot 1: {主情绪 / 视线目标与方向 / 眼皮 / 眉毛 / 嘴形 / 头部角度；没有则写 None}
Previous shot 2: {主情绪 / 视线目标与方向 / 眼皮 / 眉毛 / 嘴形 / 头部角度；没有则写 None}
Current shot: {主情绪和原因 / 当前视线目标与方向 / 眼皮 / 眉毛 / 嘴形 / 头部角度}
Across any three consecutive images, do not repeat both the same gaze direction and the same eyebrow-eye-mouth combination. If the narrative emotion remains the same, make the gaze follow a different relevant object and vary at least one additional facial cue: eyelid openness, eyebrow angle, mouth shape, or head tilt. Keep every variation semantically correct; do not rotate expressions randomly.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core knowledge relation that must stay accurate:
{不可画错的因果、方向、先后、尺度、条件或结果}

Core idea:
{这张图要表达的核心意思}

On-image information copy:
Write the following Chinese text exactly as provided; do not omit, paraphrase, duplicate, or invent text.
Core question, judgment, or conclusion: {逐字写定，1 个}
Supporting short phrases: {逐字写定，2-4 个}
Object labels if needed: {逐字写定，1-3 个}
Planned visible-character count excluding punctuation and the small Qi brand mark: {按 style-dna.md 的“文字配额”填写}
Planned text-block count: {按 style-dna.md 的“文字配额”填写}
Arrange the exact copy into the planned number of readable handwritten blocks. The text must carry the knowledge point, not merely name props. Make the core line largest, supporting phrases medium, and object labels smallest. Use clear natural black handwriting; one purple underline or one pale hand-drawn box may emphasize the key phrase.

Composition:
{具体画面：Ling 在哪里、正在做什么、主要物件是什么、信息如何流动或前后如何变化；文字块放在哪里；主体群如何整体居中并保留左右白边}

Video continuity:
{单张；或连续帧第 X/Y 张。说明上一帧状态、本帧只推进的动作，以及必须保持不变的 Ling、道具、视角和颜色}

Narrative emotion and contrast:
{当前主情绪 + 原因；与前一张/后一张是否形成转折；明确视线目标、眼神方向、眉毛、眼皮、嘴形、头部角度、躯干姿态、黑色单线手臂和步伐；说明与前两张的表情差异；列出不得出现的相反表情。例：从自建服务器的吃力切到 Vercel 拎包入住，Ling 应轻松释然、看向已经就绪的结果、眉毛放松、微笑、身体直立、步伐轻快，不得皱眉侧眼、塌肩或拖步}

Qi brand appearance:
{No；或 Yes：说明把准确拼写的小号手写文字 "Qi" 自然放在哪里。只用于品牌锚点，不做水印或标题}

Comedy beat:
{只选一个：严肃错位 / 后果显形 / 尺度反差 / 微表情吐槽 / 前后反差 / 角色误解。说明笑点发生在哪里}

Suggested elements:
{元素1} / {元素2} / {元素3} / {可选元素4}

Color use:
Match the Ling color treatment above and use the processed expression sheet as the visual color authority. These identity colors are separate from scene accents. Use mustard yellow for a friendly focal prop or attention, orange for energy, heat, change, or the main path, muted teal/blue for feedback, time, sleep, system state, or secondary information, and red only for danger, error, blockage, pain, or the key reversal. Usually use only one scene accent color.

Constraints:
One image explains only one core relation. Ling must remain the single unmistakable protagonist and be immediately recognizable as the exact same character in Images 1-2. Match identity before matching scene style. Preserve the fixed limb skeleton exactly in every pose. Match the processed expression sheet’s slightly pale overall brightness and controlled natural tonal variation across every pose; avoid alternate hues, darker or harder flat fills, exposure shifts, patchy color blocks, mottling, washed-out areas, uncontrolled gradients, or mixed saturation. The knowledge must remain factually and causally accurate. The joke supports comprehension and must not distort the concept. Ling’s gaze, facial expression, posture, and gait must match the current narrative emotion; deadpan may be subtle but must never point in the wrong emotional direction. Compare with the previous two images and prevent a three-image repetition of the same gaze direction and the same eyebrow-eye-mouth combination. When this shot contrasts with the previous or next shot, make the emotional reversal readable through at least two of eyebrows, eyes, mouth, posture, or gait. Keep the main subject around 35%-60% of the canvas and center the visual group as a whole. Preserve at least 35% empty #F5F5F7 background area, including clear side margins; do not let important content touch or cross any edge. Every image must contain meaningful, readable Chinese information copy; a text-free image fails. Render the exact copy listed above using the planned text-block count and character budget. If Qi brand appearance is Yes, write exactly "Qi" in small readable handwriting integrated into the scene; never use it as a corner watermark or large heading. Keep the information copy concise and spacious rather than forming a dense lesson slide. Do not write a structure-type heading in the top-left corner. Do not make it a formal diagram, course slide, reaction meme, or multi-panel collage unless the selected structure is a 2-4 frame mini-comic. Do not copy reference-video scenes, character designs, or prior examples. Invent a fresh, simple visual metaphor for this specific script. It should be accurate first, funny second, clear immediately, and retain an adult cartoon tone.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same solid #F5F5F7 background (RGB 245, 245, 247), matching the surrounding empty area. Preserve everything else exactly: Ling, labels, props, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强 Ling 的参与感与笑点：

```text
Regenerate this illustration with the same accurate core knowledge relation and simple layout, but make Ling central to the conceptual action. Use all three anchor references. Ling should operate or experience the mechanism and add one restrained deadpan comedy beat through pose or micro-expression, not stand beside the diagram. Keep the exact soft rounded face, long straight black hair, thin round glasses, lavender T-shirt, exaggerated head-to-body ratio, and fixed single-black-line limb skeleton. Compare with the previous two images and avoid a three-image repetition of the same gaze and facial combination. Keep it clean, sparse, hand-drawn, original, intelligent, and adult.
```

纠正 Ling 的四肢骨架：

```text
Edit or regenerate this illustration while preserving the knowledge relation, scene, Ling face, hair, glasses, lavender torso, expression, colors, labels, props, composition, aspect ratio, and #F5F5F7 background. Change only Ling’s limbs to match Image 2 exactly: two continuous thin black single-line arms emerging from the lavender torso sides, each ending in a small solid black circular or oval hand; two continuous thin black single-line legs emerging from the torso bottom, each ending in a slightly larger solid black oval foot. Preserve the intended pose by changing only line direction and contact points. Remove lavender sleeve-shaped arms, skin-colored arms or hands, palms, fingers, thumbs, wrists, double-line limbs, anatomical volume, pants legs, knees, calves, shoes, broken connections, extra limbs, and missing visible limbs. After editing, every visible limb must pass the fixed limb skeleton gate.
```

纠正 Ling 的表情与叙事情绪：

```text
Edit or regenerate the illustration while preserving the knowledge relation, exact Ling identity from both original character assets, props, composition, labels, line style, colors, aspect ratio, and solid #F5F5F7 background (RGB 245, 245, 247). Change only Ling’s facial expression and supporting body language so they clearly express {目标情绪及原因}. Specify eyebrows, eyes, mouth, posture, arms, and gait. This shot contrasts with {前一状态}; make the emotional reversal immediately readable but restrained and adult. Remove any conflicting cues such as {皱眉 / 侧眼 / 塌肩 / 拖步 / 冷汗}.
```

纠正连续三张表情重复：

```text
Edit or regenerate only the third illustration in this three-image sequence. Preserve the knowledge relation, scene, Ling identity, fixed limb skeleton, pose intention, props, composition, labels, line style, colors, aspect ratio, and #F5F5F7 background. Keep Ling’s correct main emotion, but remove the three-image facial repetition. In Image 3, make Ling look specifically at {当前相关对象} with a {左 / 右 / 上 / 下 / 正前方} gaze that differs from Images 1-2, and change at least one additional cue among eyelid openness, eyebrow angle, mouth shape, or head tilt. The new expression must follow the current meaning and attention target, not look randomly different. Do not alter Images 1-2.
```

补充或纠正信息文字：

```text
Edit the illustration while preserving Ling’s exact identity, fixed limb skeleton, expression, pose, props, knowledge relation, color treatment, line style, composition, aspect ratio, and solid #F5F5F7 background. Make the image carry its knowledge point through concise readable Chinese handwriting. Write exactly these text blocks: {逐字列出核心句、辅助短句和必要物件标签}. Keep a total of {目标字符数} visible characters excluding punctuation and the small Qi mark, arranged as {目标文字块数} spacious blocks with a clear hierarchy: one largest core question, judgment, or conclusion; medium supporting phrases; smallest object labels. Remove any other invented or duplicated wording. Correct every missing, wrong, garbled, or unreadable character. Keep the illustration-like composition and ample negative space; reduce a secondary prop if space is needed.
```

减少搞笑、提高准确性：

```text
Edit or regenerate the illustration so the factual relationship is immediately clear and correct. Keep Ling and the same visual style, but remove any gag, prop, label, or exaggeration that could misrepresent the concept. Retain at most one subtle deadpan reaction after the knowledge structure is clear.
```

纠正 Ling 上衣颜色：

```text
Edit or regenerate this illustration while preserving the knowledge relation, scene, Ling face, hair, glasses, fixed limb skeleton, expression, props, composition, labels, line style, aspect ratio, and #F5F5F7 background. Change ONLY Ling's short-sleeve T-shirt to a clearly visible solid lavender light purple flat fill, color approximately #C69BC8, matching the reference assets. The purple shirt must cover the entire visible torso area. Remove white, gray, cream, or uncolored line-art-only shirt. Do not change anything else.
```
