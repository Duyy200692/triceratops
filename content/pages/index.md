---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Unblock your team boost your time to production
      color: text-dark
      type: TitleBlock
    subtitle: Subtitle goes here
    text: >
      A Netlify Create website is a git repo that you own. Every code commit is
      instantly reflected in the visual editor and since every visual edit is a
      git commit, git workflows and collaboration just work.
    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: See Tutorials
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: This is a badge
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: List of features here
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: Featured items section subtitle
    items:
      - type: FeaturedItem
        title: ROBUSTA
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first Netlify site.
        image:
          type: ImageBlock
          url: /images/triceratops - ro.png
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: ARABICA
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first awesome Netlify site.
        image:
          type: ImageBlock
          url: /images/triceratops - arabica.png
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: BLEND
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Learn from the tutorial and build your first awesome Netlify site.
        image:
          type: ImageBlock
          url: /images/triceratops - blend.png
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
    actions: []
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
  - subtitle: Award winning enterprises trust us
    images:
      - url: /images/empathy-logo.svg
        altText: Empathy logo
        type: ImageBlock
      - url: /images/wellster-logo.svg
        altText: Wellster logo
        type: ImageBlock
      - url: /images/vise-logo.svg
        altText: Vise logo
        type: ImageBlock
      - url: /images/telus-logo.svg
        altText: Telus logo
        type: ImageBlock
      - url: /images/contenful-logo.svg
        altText: Contentful logo
        type: ImageBlock
      - url: /images/sanity-logo.svg
        altText: Sanity logo
        type: ImageBlock
      - url: /images/rangle-logo.svg
        altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Grow your business 10x faster
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: This is a subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    media:
      title: Title of the video
      url: /images/placeholder-video.mp4
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
      autoplay: true
      loop: true
      muted: true
    badge:
      label: Key Benefits
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
  - type: GenericSection
    title:
      text: Generic section with a video
      color: text-dark
      styles:
        self:
          textAlign: left
      type: TitleBlock
    subtitle: Section with a video subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      title: Title of the video
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
    elementId: null
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - title:
      text: Social Media Management
      color: text-dark
      type: TitleBlock
    subtitle: Increase your reach
    text: >
      A service that helps businesses to manage their social media accounts and
      posts.
    actions:
      - label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero2.svg
      altText: Fun feature preview
      type: ImageBlock
    badge:
      label: This is a badge
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
    type: GenericSection
  - title:
      text: Business Consulting
      color: text-dark
      type: TitleBlock
    subtitle: Be in good company
    text: >
      A service that provides advice and guidance to startups and small
      businesses.
    actions:
      - label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/hero3.svg
      altText: Dope design preview
      type: ImageBlock
    badge:
      label: This is a badge
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - type: CarouselSection
    title: null
    subtitle: What our customers say about us
    items:
      - title: Cà Phê Chất Lượng Cao Có Gì Khác Biệt?
        tagline: Testimonial 1
        subtitle: trico.coffee
        text: "#### CÀ PHÊ CHẤT LƯỢNG CAO CÓ GÌ KHÁC BIỆT?\n\n#### Cà phê luôn được biết đến là một trong những loại đồ uống ngon và được ưa chuộng nhất thế giới. Đối với nhiều người, cà phê không chỉ đơn giản là một loại thức uống mà nó còn là một phong cách sống, một nét văn hoá đặc biệt. Và cũng vì thế, nhu cầu thưởng thức cà phê của mỗi người ngày một tăng. Họ cần cà phê phải thực sự chất lượng, hương vị tinh tế, có lợi cho sức khoẻ và đặc biệt họ còn tìm hiểu về nguồn gốc, phương thức canh tác, sơ chế, chế biến của thứ họ đang dùng. Đó cũng chính là những gì cà phê chất lượng cao có thể\_mang lại.\n\n#### Cà phê chất lượng cao là gì?\n\n#### Cà phê chất lượng cao là thành phẩm của quá trình thu hái, chọn lọc, sơ chế chuẩn theo quy định của Hiệp hội cà phê thế giới. Sản phẩm này có sự rõ ràng về nguồn gốc, được chịu trách nhiệm bởi vùng trồng, nông dân và công ty sản xuất, đảm bảo không vị trộn lẫn với cà phê đại trà.\n\n#### Do quá trình sơ chế khá phức tạp, đòi hỏi sự kiểm soát chặt chẽ, cà phê chất lượng cao thường được sản xuất với số lượng có hạn. Và cũng nhờ quy trình này, cà phê chất lượng cao mang lại những ưu điểm khác biệt mà các dòng cà phê phổ thông không có được. Tuy nhiên, cà phê chất lượng cao vẫn đứng dưới cà phê đặc sản một bậc trên thang điểm chất lượng.\n\n####\n\n#### Cà phê chất lượng cao có gì khác biệt?\n\n#### Chất lượng thu hoạch\n\n#### Cà phê chất lượng cao được thu hái một cách có chọn lọc, chỉ hái trái chín đỏ, tỷ lệ chín tối thiểu khoảng 95%, nhiều nơi đảm bảo tỷ lệ chín lên đến 100%. Cà phê hái chín sẽ đem lại vị ngọt tự nhiên cho nhân cà phê nhờ vào lớp thịt quả. Đó cũng là lý do các loại cà phê chất lượng cao thường có hậu vị ngọt dịu.\n\n####\n\n#### Quá trình sơ chế\n\n#### Cà phê chất lượng cao có thể áp dụng nhiều phương pháp sơ chế khác nhau, theo đúng phương pháp sơ chế cà phê đặc sản. Trong đó, sơ chế mật ong là phương pháp sơ chế cà phê chất lượng cao được sử dụng nhiều nhất hiện nay. Ngoài ra, quá trình phơi khô cũng được thực hiện một cách tỉ mỉ chứ không phơi đại ra đất hoặc sấy khô như cà phê truyền thống.\n\n#### Ngoài sơ chế Honey, cà phê chất lượng cao vẫn có thể được sơ chế theo những phương pháp khác như sơ chế khô, sơ chế ướt, sơ chế bán ướt.\n\n#### Chất lượng nhân\n\n#### Cà phê chất lượng cao thường có chất lượng nhân vượt trội hơn nhiều so với cà phê đại trà. Nhờ quá trình phơi trên giàn lưới, cách đất nên cà phê không bị ám mùi đất, tạp chất. Sau khi phơi khô, sản phẩm này sẽ được loại bỏ các khiếm khuyết như nhân đen, vỡ, vỏ khô, tạp chất,… bằng các loại máy móc chuyên dụng hoặc thủ công. Theo đó, cà phê chất lượng cao không chỉ đảm bảo tiêu chí về hương vị, chất lượng mà còn an toàn tuyệt đối cho sức khoẻ người dùng.\n\n#### Hương vị\n\n#### Cà phê chất lượng cao sau khi rang xay sẽ đem lại cảm giác sảng khoái cho người dùng. Nước cà phê trong, có cảm giác sạch khi uống trong miệng, hương thơm đặc trưng và đặc biệt nhất vẫn là hậu vị ngọt dịu đầy hấp dẫn.\n\n####\n\n#### Kiểm soát chất lượng, thử nếm\n\n#### Quá trình thử nếm là công đoạn cực kỳ quan trọng trong chế biến cà phê đặc sản và cà phê chất lượng cao. Những chuyên gia về cà phê sẽ kiểm tra hương vị, chất lượng để tạo nên sản phẩm ưu việt nhất, phù hợp với nhu cầu của khách hàng. Một lô cà phê, một mẻ rang thường sẽ được thử nếm ít nhất 3 lần trước khi được phê chuẩn, bắt đầu chinh phục khách hàng.\n\n#### Giá trị cộng đồng\n\n#### Như đã nói, cà phê chất lượng cao không chỉ là một loại thức uống mà còn là nét văn hoá, là phong cách sống và đặc biệt đó cũng là trách nhiệm với cộng đồng. Tương lai của cà phê chất lượng cao chính là tương lai của những người nông dân cần mẫn. Cà phê chất lượng cao đem đến hiệu quả kinh tế cao hơn và tạo dựng được hình ảnh cà phê Việt Nam tốt hơn nhiều so với cà phê đại trà. Điều này dẫn đến một cuộc sống tốt đẹp hơn cho nông dân và tất nhiên, ly cà phê của chúng ta cũng tốt, cũng ngon và ý nghĩa hơn nhiều.\n\n#### Cà phê chất lượng cao hiện nay chưa được phổ biến rộng rãi như các loại cà phê đại trà. Hơn nữa, với quá trình sản xuất cực kỳ phức tạp, cà phê chất lượng cao thương có giá thành cao hơn nhiều. Tuy nhiên, trong vài năm tới, dòng sản phẩm này chắc chắn sẽ là sự lựa chọn hàng đầu trong cộng đồng cà phê Việt Nam cũng như xuất khẩu.\n\n#### \n\n\n\n"
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Design is a plan for arranging elements in such a way as best to
          accomplish a particular purpose."
        tagline: Testimonial 2
        subtitle: 'John Doe, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: John Doe
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Design is how it works, how it functions. Good design doesn't just
          make a product aesthetically pleasing, it makes it a pleasure to use."
        tagline: Testimonial 3
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          “A designer knows he has achieved perfection not when there is nothing
          left to add, but when there is nothing left to take away.”
        tagline: Testimonial 4
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Design can be art. Design can be aesthetics. Design is so simple,
          that's why it is so complicated."
        tagline: Testimonial 5
        subtitle: 'Jane Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          “Quote from some important person goes right here. I love using
          Netlify Create.”
        tagline: Testimonial 6
        subtitle: 'Jane Doe, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/img-placeholder-dark.png
          altText: Jane Doe
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
    elementId: null
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: List of features here
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Featured items section subtitle
    items:
      - title: Feature Item One
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first Netlify Create site.
        image:
          url: /images/abstract-feature1.svg
          altText: Placeholder Image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Feature Item Two
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first awesome Netlify Create site.
        image:
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Feature Item Three
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: >
          Learn from the tutorial and build your first awesome Netlify Create
          site.
        image:
          url: /images/abstract-feature1.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
  - title:
      text: Generic Section With A Form
      color: text-dark
      type: TitleBlock
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
  addTitleSuffix: false
type: PageLayout
---
