<template>
  <v-app>
    <v-app-bar
      app
      :color="navColor"
      height="100"
      :style="[
        { boxShadow: navColor === 'transparent' ? '0 0 0 0' : '0 0 10px #000' },
      ]"
    >
      <v-toolbar-title class="font-weight-black headline">
        SEBA
      </v-toolbar-title>
    </v-app-bar>

    <v-main>
      <section id="hero" style="margin-top: -100px">
        <v-row no-gutters>
          <video
            ref="vid"
            autoplay
            controls
            style="width: 100vw; background-color: #000"
            @ended="handleVideoEnding"
          >
            <source src="/videos/intro.mp4?autoplay=1" />
          </video>
        </v-row>
      </section>

      <section id="about-me">
        <div class="py-12"></div>

        <v-container class="text-center">
          <h2 class="dis-2 font-weight-bold mb-3 cairo-font">سيبا</h2>

          <v-responsive class="mx-auto mb-8" width="56">
            <v-divider class="mb-1"></v-divider>

            <v-divider></v-divider>
          </v-responsive>

          <v-responsive
            class="mx-auto title font-weight-light mb-8"
            max-width="720"
          >
            <br />
            سيبا رمز هيلوغريفي يعني "نجمة"، و قد اعتاد اجدادنا تلقيب المعلمين
            بلقب "سيباو" و هو يعني النجمة المرشدة، تشبيهاً للمعلمين بالنجوم التي
            ترشدهم في دروب حياتهم.
          </v-responsive>
        </v-container>

        <v-container class="text-center">
          <h2 class="dis-2 font-weight-bold mb-3 cairo-font">
            المقدمة و الفكرة
          </h2>

          <v-responsive class="mx-auto mb-8" width="56">
            <v-divider class="mb-1"></v-divider>

            <v-divider></v-divider>
          </v-responsive>

          <v-responsive
            class="mx-auto title font-weight-light mb-8"
            max-width="720"
          >
            <br />
            تعتزم رؤية مصر 2030 أنه بحلول هذا العام إتاحة التعليم والتدريب
            للجميع بجودة عالية دون التمييز، وفي إطار نظام مؤسسي، وكفء وعادل،
            ومستدام، ومرن، وأن يكون مرتكزًا على المتعلم والمتدرب القادر على
            التفكير والمتمكن فنياً وتقنياً وتكنولوجياً، وأن يساهم أيضاً في بناء
            الشخصية المتكاملة وإطلاق إمكانياتها إلى أقصى مدى لمواطن معتز بذاته،
            ومستنير، ومبدع، ومسئول، وقابل للتعددية، يحترم الاختلاف، وفخور بتاريخ
            بلاده، وشغوف ببناء مستقبلها وقادر على التعامل تنافسياً مع الكيانات
            الإقليمية والعالمية.
            <br /><br />
            وفي ضوء ذلك جاءت فكرت عمل منصة الكترونية تضم جميع مراحل التعليم قبل
            الجامعي (ابتدائي – اعدادي – ثانوي) بنوعيه الخاص والحكومة مع مراعاة
            جميع طبقات المجتمع دون تفرقة تتيح للطالب التعلم عن بعد او من منازلهم
            وفق مناهج التعليم المصرية مع إمكانية تقييمهم ومعرفة نقاط القوة
            والضعف لديهم للعمل عليها من اجل مستقبل افضل لهم مما ينعكس علي
            انتاجيتهم في النهوض بالدولة
            <br /><br />
            الحد من جشع المدرسين الخصوصيين والمراكز التعليمية لإتاحة التعليم
            لكافة الطبقات بغض النظر عن مستواهم المادي تفعيل وتدعيم دور الاسرة في
            بناء وتقييم الطالب
          </v-responsive>
        </v-container>

        <v-container class="text-center">
          <h2 class="dis-2 font-weight-bold mb-3">الأهداف العامة</h2>

          <v-responsive class="mx-auto mb-8" width="56">
            <v-divider class="mb-1"></v-divider>

            <v-divider></v-divider>
          </v-responsive>

          <v-responsive
            class="mx-auto title font-weight-light mb-8"
            max-width="720"
          >
            التحول الرقمي والشق التربوي في نظام التعليم المصري وربطه بنظام
            الامتحانات والتصحيح الالكتروني لتحويل النظام التعليمي ليصبح نظام
            الكتروني متكامل
            <br />
            <br />
            تعديل مفهوم التعليم الالكتروني الخاطئ السائد في المجتمع لمفهومه
            الأصلي انه تعليم الكتروني اجتماعي مشترك
            <br />
            <br />
            التحول بالطالب من مستلقي للمعلومة لباحث ومصدر للمعلومة ليصبح هو محور
            العملية التعليمية
          </v-responsive>
        </v-container>

        <div class="py-12"></div>
      </section>

      <section id="features" class="">
        <div class="py-12"></div>

        <v-container class="text-center">
          <v-parallax
            :height="$vuetify.breakpoint.smAndDown ? 400 : 200"
            src="/imgs/stars.jpg"
          >
            <v-container fill-height>
              <v-row class="mx-auto" align="center" justify="center">
                <h1 class="dis-2 font-weight-bold text-center">
                  المزايا و المنافع
                </h1>
              </v-row>
            </v-container>
          </v-parallax>

          <v-responsive class="mx-auto mb-12" width="56">
            <v-divider class="mb-1"></v-divider>

            <v-divider></v-divider>
          </v-responsive>

          <v-row>
            <v-col
              v-for="({ icon, title, text }, i) in features"
              :key="i"
              cols="12"
              md="4"
            >
              <v-card class="py-12 px-4" style="min-height: 600px" flat>
                <v-theme-provider dark>
                  <div>
                    <v-avatar color="primary" size="88">
                      <v-icon large v-text="icon"></v-icon>
                    </v-avatar>
                  </div>
                </v-theme-provider>

                <v-card-title
                  class="justify-center font-weight-black text-uppercase"
                  v-text="title"
                ></v-card-title>

                <v-card-text style="font-size: 110%">
                  <ul class="text-right">
                    <li
                      v-for="(point, p) in text"
                      :key="p"
                      class="mb-3"
                      v-text="point"
                    />
                  </ul>
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </v-container>

        <div class="py-12"></div>
      </section>

      <section id="stats">
        <v-parallax
          :height="$vuetify.breakpoint.smAndDown ? 400 : 200"
          src="/imgs/stars.jpg"
        >
          <v-container fill-height>
            <v-row class="mx-auto" align="center" justify="center">
              <h1 class="dis-2 font-weight-bold text-center">
                اليات الاستخدام
              </h1>
            </v-row>
          </v-container>
        </v-parallax>
      </section>
      <section>
        <v-container>
          <v-row align="center">
            <v-col cols="12" md="3" class="hidden-md-and-down">
              <v-img src="/imgs/teacher.png" max-height="50vh" contain />
            </v-col>
            <v-col cols="12" md="9">
              <h1 class="text-right">كيفية العمل ( المدرس )</h1>
              <br />
              <p class="text-right">
                استخدام المعلم يقوم بمليء استمارة بيانات الدخول لا يوجد شروط
                لانضمام أي معلم لتجميع اكبر عدد من المعلمين ولكن يوجد شروط
                واحكام اثناء العملية التعليمية وتقييم مستمر له من الممكن ان يؤدي
                الي وقف مزاولته النشاط علي المنصة
                <br /><br />
                سيقوم المعلم بإرسال فيديو تجريبي لطريقة شرحه ويتم تقييمه
                الكترونيا بناء علي عدة مقومات
                <br /><br />
                يتم عمل جدول زمني للشهر بالكامل كقسم لعدة مجموعات تتيح للطلاب
                الاشتراك في الميعاد المناسب لها
                <br /><br />
                توفير ميزه تنافسية من خلال المنصة تتيح للمعلم كسب المال اكثر من
                أي منصة اخري واكثر من الدروس الخصوصية العادية وذلك من خلال طريقة
                رياضية خوارزمية معينة تجعله يجني اضعاف مكاسبه من الدروس وتجعل
                الطلاب يدفعون اقل بكثير مما كانوا عليه
                <br /><br />
                توفير الوقت والمجهود للمعلم يجعله يمارس عمله بشكل اكبر وافضل
              </p>
            </v-col>
          </v-row>
        </v-container>
        <v-container>
          <v-row align="center">
            <v-col cols="12" md="9">
              <h1 class="text-right">كيفية العمل ( للطالب)</h1>
              <br />
              <p class="text-right">
                يقوم الطالب بالتسجيل في المنصة وتحديد السنة الدراسية والمواد
                المراد دراستها
                <br /><br />
                يستعرض الطالب المدرسين في كل المواد حسب المادة وتقييم الطلاب له
                وحسب التوزيع الجغرافي
                <br /><br />
                يختار طالب مدرس ويطلب الاشتراك معه او طلب ترشيح مدرس له
                <br /><br />
                يقوم الطالب بالاشتراك في المواد المرغوب فيها ودفع رسومها شهريا
                عن طريق منافذ الدفع الالكترونية المختلفة
                <br /><br />
                يحضرالطالب الدروس والفعاليات مع المدرس مع وجود جزء ترفيهي لكل
                ماده لتسهيل المذاكرة
                <br /><br />
                يستطيع الطالب تقييم المدرس
                <br /><br />
                يتم تقييم الطالب بصفة دورية الكترونيا وتحديد مستواه لكل ماده
                وارسال وسائل تقوية له من مقالات او فيديو او اسئلة
              </p>
            </v-col>
            <v-col cols="12" md="3" class="hidden-md-and-down">
              <v-img src="/imgs/student.png" max-height="50vh" contain />
            </v-col>
          </v-row>
        </v-container>
        <v-container>
          <v-row align="center">
            <v-col cols="12" md="3" class="hidden-md-and-down">
              <v-img src="/imgs/mom.png" max-height="50vh" contain />
            </v-col>
            <v-col cols="12" md="9">
              <h1 class="text-right">المتابعة والأشراف (الأسرة)</h1>
              <br />
              <p class="text-right">
                توفر المنصة اليه لأولياء الأمور لمتابعه مستوي ابنائهم وتقدمهم في
                العملية التعليمية
                <br /><br />
                إمكانية متابعة مستوي الأبناء عن طريق رسائل نصية تشمل تقييم مستمر
                للطالب سواء في الدراسة او الامتحانات التجريبية الدورية
                <br /><br />
                توفير دورات تدريبية للأسرة لمعرفة طرق التربية السليمة والتي
                تتناسب مع شخصية أبنائهم
              </p>
            </v-col>
          </v-row>
        </v-container>
        <v-container>
          <v-parallax
            :height="$vuetify.breakpoint.smAndDown ? 400 : 200"
            src="/imgs/stars.jpg"
          >
            <v-container fill-height>
              <v-row class="mx-auto" align="center" justify="center">
                <h1 class="dis-2 font-weight-bold text-center">
                  قوة الذكاء الاصطناعي
                </h1>
              </v-row>
            </v-container>
          </v-parallax>
          <v-row align="center" class="text-center" justify="center">
            <v-col cols="12" md="8">
              <h3 class="dis-3 font-weight-bold text-right mb-5">
                تكنولوجيا المعلومات والذكاء الاصطناعي وأثرهم علي المنظومة
                التعليمية
              </h3>
              <p style="font-size: 120%" class="text-right">
                تحليل أداء الطلاب وتقييمهم دراسيا واجتماعيا ومعرفة ميولهم مما
                يعطي تنبؤات بالمجالات التي يرغب بها الطلاب
                <br /><br />
                الحد من نفقات التعليم الباهظة للأهالي في الدروس الخصوصية وخلافه
                حيث حيث ان معظم الاسر تنفق ما يقرب من 50 % من دخلهم التقييم
                الفعلي علي أداء المعلمين والعمل علي التحسين من أدائهم
                <br /><br />
                زيادة قدرة الأسرة من معرفة الطرق المثلي لتربية الأبناء مما ينعكس
                علي المجتمع ككل
                <br /><br />
                تحويل الفيديوهات الي مقالات توظف كمواد علمية للطلاب تحديد شخصيه
                المدرس ومعرفة كيفية توظيفيه المراجعات والنهائية والامتحانات
                الدورية تحت اشراف وتعليمات الوزاره
                <br /><br />
                صياغة المناهج والاسئلة بشكل ترفيهي في شكل العاب وغيره عمل
                مسابقات بين الطلبة وتقديم جوائز لهم من خلال الشركات الراعية
                <br /><br />
                عمل منصة تواصل داخلية بين مجتمع المنصة كاملا تدعيم الإعلانات علي
                المنصة وهو ما يحقق عائد كبير من الأرباح
              </p>
            </v-col>
          </v-row>
        </v-container>
      </section>

      <section id="blog">
        <v-parallax
          :height="$vuetify.breakpoint.smAndDown ? 400 : 200"
          src="/imgs/stars.jpg"
        >
          <v-container fill-height>
            <v-row class="mx-auto" align="center" justify="center">
              <h1 class="dis-2 font-weight-bold text-center">منصات العمل</h1>
            </v-row>
          </v-container>
        </v-parallax>
        <div class="py-12"></div>
        <v-container>
          <v-row justify="center">
            <v-col cols="12" md="8">
              <p style="font-size: 120%">
                ستقوم المنصة بخدمة انواع مختلفة من المستخدمين كالطلاب و المعلمين
                و اولياء الأمور و موظفين التشغيل و الجهات الإدارية.
                <br />
                ولذلك فمن الضروري توفير منصات مختلفة لقطاعات المستخدمين مما يوفر
                اداء افضل لكل منصة على حدى و تجربة استخدام اسهل و اكثر تركيزاً
                على مهام تلك القطاعات .<br />
                توفير المنصات على انواع مختلفة من الأجهزة سيجعلها متاحة لجميع
                القطاعات في اي وقت بسهولة.
                <br />
              </p>
            </v-col>
          </v-row>
          <h3 class="dis-25 font-weight-bold mb-10 mt-5 text-center grey--text">
            المنصات حسب المستخدمين
          </h3>
          <v-row>
            <v-col cols="12" md="3" class="text-center">
              <h3 class="dis-3 font-weight-bold mb-5">
                الطلبة و اولياء الأمور
              </h3>
              <v-icon style="font-size: 6rem">mdi-apple</v-icon>
              <p>تطبيق IOS</p>
              <v-icon style="font-size: 6rem" class="green--text">
                mdi-android
              </v-icon>
              <p>تطبيق Andriod</p>
              <v-icon style="font-size: 6rem" class="blue--text">
                mdi-web
              </v-icon>
              <p>تطبيق Web</p>
            </v-col>
            <v-col cols="12" md="3" class="text-center">
              <h3 class="dis-3 font-weight-bold mb-5">المعلمين</h3>
              <v-icon style="font-size: 6rem">mdi-apple</v-icon>
              <p>تطبيق IOS</p>
              <v-icon style="font-size: 6rem" class="green--text">
                mdi-android
              </v-icon>
              <p>تطبيق Andriod</p>
              <v-icon style="font-size: 6rem" class="blue--text">
                mdi-web
              </v-icon>
              <p>تطبيق Web</p>
            </v-col>
            <v-col cols="12" md="3" class="text-center">
              <h3 class="dis-3 font-weight-bold mb-5">موظفين التشغيل</h3>
              <v-icon style="font-size: 6rem" class="blue--text">
                mdi-web
              </v-icon>
              <p>تطبيق Web</p>
            </v-col>
            <v-col cols="12" md="3" class="text-center">
              <h3 class="dis-3 font-weight-bold mb-5">الجهات الإدارية</h3>
              <v-icon style="font-size: 6rem">mdi-apple</v-icon>
              <p>تطبيق IOS</p>
              <v-icon style="font-size: 6rem" class="green--text">
                mdi-android
              </v-icon>
              <p>تطبيق Andriod</p>
              <v-icon style="font-size: 6rem" class="blue--text">
                mdi-web
              </v-icon>
              <p>تطبيق Web</p>
            </v-col>
          </v-row>
        </v-container>
        <div class="py-12"></div>
      </section>
      <section id="concepts">
        <v-parallax
          :height="$vuetify.breakpoint.smAndDown ? 500 : 300"
          src="/imgs/layers.gif"
        >
          <v-container fill-height>
            <v-row class="mx-auto" align="center" justify="center">
              <h1 class="dis-2 font-weight-bold text-center">
                اساسيات التصميم
              </h1>
            </v-row>
          </v-container>
        </v-parallax>
        <div class="py-12"></div>
        <v-container>
          <v-row align="center" class="text-center" justify="center">
            <v-col cols="12" md="8">
              <h3 class="dis-3 font-weight-bold text-right mb-5">
                التحديات التقنية
              </h3>
              <br />
              <p style="font-size: 120%" class="text-right">
                من المقرر ان تخدم المنصة ملايين من الطلبة، و ملايين من اولياء
                الأمور، و الاف من المعلمين.
                <br /><br />
                مما يجعل الأداء و السرعة و القدرة على إستيعاب اعداد ضخمة شرط
                اساسي من شروط نجاح المنصة.
                <br /><br />
                يعتبر مجال التعليم بشكل عام من المجالات المطورة لذاتها، فكل يوم
                هناك العديد من النشاطات الجديدة تظهر على الساحة، لذلك فإنشاء
                منصة قادرة على مواكبة تلك النشاطات ليس برفاهية.
              </p>
              <h3 class="dis-3 font-weight-bold text-right mb-5 mt-10">
                المفاتيح الرئيسية في التصميم
              </h3>
              <ul class="text-right mr-5" style="font-size: 120%">
                <li>سرعة الأداء</li>
                <li>قابلية التوسع</li>
                <li>المرونة</li>
              </ul>
              <br />
            </v-col>
          </v-row>
        </v-container>
      </section>
      <section>
        <v-parallax
          :height="$vuetify.breakpoint.smAndDown ? 700 : 400"
          src="/imgs/brain.jpg"
        >
          <v-container fill-height>
            <v-row class="mx-auto" align="center" justify="center">
              <h1 class="dis-2 font-weight-bold text-center">
                التكنولوجيا المستخدمة
              </h1>
            </v-row>
          </v-container>
        </v-parallax>
        <v-container>
          <h1 class="dis-2 text-center">Databases</h1>

          <v-row justify="center" align="center">
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="0"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/mongodb.png" />
              <p class="hidden-md-and-up text-center">Mongo</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/cassandra.png" />
              <p class="hidden-md-and-up text-center">Cassandra</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/mysql.png" />
              <p class="hidden-md-and-up text-center">MySQL</p>
            </v-col>
          </v-row>
          <v-row justify="center" align="center" class="hidden-md-and-down">
            <v-col cols="12" :md="1">
              <p class="text-center">Mongo Database</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center">Cassandra Database</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center">MySQL Database</p>
            </v-col>
          </v-row>
          <p>
            ستقوم المنصة بتخزين كم هائل من البيانات و التي بطبيعة عمل المنصة سوف
            تأخذ انماط متعددة.
            <br /><br />
            تلك البيانات تمثل مصدر قوة هائل للمنصة اذا ما تم التعامل معها بشكل
            صحيح.<br /><br />
            لذلك فنحن نستخدم قواعد بيانات Mongo فيما يتعلق بالبيانات الممنهجة و
            التي من المقرر دراستها فيما بعد لتدعيم المنصة بأمناط سيتم استنتاجها
            بالذكاء الإصطناعي.<br /><br />
            كما نقوم باستخدام Cassandra لكونها افضل قواعد البيانات متعددة
            النواة، و الذي بدوره سيساعدنا بشكل اساسي في التوسع دون ان يتضرر اداء
            المنظومه.<br /><br />
            فيما يخص البيانات غير متذبذبة الهيئة، MySQL توفر اداء منقطع النظير
            اذا ما قارناها بما يعادلها من قواعد البيانات المعتمدة على نفس النهج.
            <br /><br />
          </p>

          <!--backend -->
          <h1 class="dis-2 text-center">Server Mirco Services</h1>
          <v-row justify="center" align="center">
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="0"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/node.png" />
              <p class="hidden-md-and-up text-center">NodeJS</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/go.png" />
              <p class="hidden-md-and-up text-center">GoLang</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/cpp.png" />
              <p class="hidden-md-and-up text-center" dir="ltr">C++</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/elixir.png" />
              <p class="hidden-md-and-up text-center">Elixir</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/python.png" />
              <p class="hidden-md-and-up text-center">Python</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/php.png" />
              <p class="hidden-md-and-up text-center">PHP</p>
            </v-col>
          </v-row>
          <v-row justify="center" align="center" class="hidden-md-and-down">
            <v-col cols="12" :md="1">
              <p class="text-center">NodeJS</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center">GoLang</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center" dir="ltr">C++</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center">Elixir</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center">Python</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center">PHP</p>
            </v-col>
          </v-row>
          <p>
            ستقوم خوادم المنصة بتوفير العديد من الخدمات المختلفة و تقديمها
            لملايين المستخدمين.
            <br /><br />
            لذلك فلابد ان يكون تصميم تلك الخدمات معتمد بشكل كامل على نمط الخدمات
            الصغيرة Micro Services و الذي سيمكننا من تصميم الخدمات بشكل افضل و
            سيوفر المرونة المطلوبة لإضافة خدمات جديدة بشكل مستمر.
            <br /><br />
            كما ان هذا النمط سيساعد بشكل اساسي في رفع اداء المنظومة حيث يمكننا
            رفع كفائة الخوادم التي تعمل تحت ضغط اكثر، مما سيقلل تكاليف رفع كفائة
            المنصة و يحسن ادائها و يوفر لها معدلات امان اعلى.
            <br /><br />
            نمط الخدمات الصغيرة يسمح لنا باستخدام العديد من لغات البرمجة و الذي
            بدورة يعطينا ميزة استخدام الافضل حسب نوع الخدمة نفسها.
            <br /><br />
            فمثلاً نستخدم NodeJS فيما يخص التوسع و الخدمات التي تعتمد على
            التزامن كالمراسلات و التفاعل بين الطلبة و المعلم.
            <br />
            و هو ما تفعله مؤسسات عملاقة بالفعل بإستخدامها مثل Facebook و Paypal
            و Netflix و Nasa و Ebay و Uber
            <br /><br />
            و فيما يخص التعامل مع انماط البيانات المعقدة و والوسائط المتعددة,
            GoLang توفر اداء ممتاز في التعامل مع تلك الأمور.
            <br />
            و هو ما تفعله مؤسسات عملاقة بالفعل بإستخدامها مثل Google و Uber و
            Dailymotion و Dropbox
            <br /><br />
            اما عن خدمات البث المباشر و توفير المحتوى بشكل سريع فنستخدم Elixir و
            التي تعتبر رائدة في هذا المجال
            <br />
            تقوم كل من Whatsapp و Netflix و BleacherReport و Pintrest باستخدام
            Elixir لنفس الاغراض تقريبا.
            <br /><br />
            اما في مجالات الذكاء الإصطناعي و دراسة البيانات فنقوم باستخدام
            Python و C++ بتفاوتات مختلفة لنحقق التوازن بين الانجاز و الاداء
            <br />
            سنجد ان استخدام تلك اللغات ليس برفاهية في معظم المؤسسات العملاقة و
            الذين يستخدمون نفس المزيج مثل Google و Facebook و Netflix و
            Instagram و غيرهم الكثير.
            <br /><br />
          </p>

          <h1 class="dis-2 text-center">Client Portals</h1>
          <p>lorem ipsum</p>
          <v-row justify="center" align="center">
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="0"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/vue.png" />
              <p class="hidden-md-and-up text-center">VUE PWA</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/nuxt.png" />
              <p class="hidden-md-and-up text-center">Nuxt SSR</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/swift.png" />
              <p class="hidden-md-and-up text-center">Swift</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/kotlin.png" />
              <p class="hidden-md-and-up text-center">Kotlin</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/flutter.png" />
              <p class="hidden-md-and-up text-center">Flutter</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/webrtc.png" />
              <p class="hidden-md-and-up text-center">WebRTC</p>
            </v-col>
          </v-row>
          <v-row justify="center" align="center" class="hidden-md-and-down">
            <v-col cols="12" :md="1">
              <p class="text-center">VUE PWA</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center">NUXT SSR</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center" dir="ltr">Swift</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center">Kotlin</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center">Flutter</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center">WebRTC</p>
            </v-col>
          </v-row>
          <p>
            اما عن منصات المستخدمين فتوفر المنصة العديد منهم لكل من قطاعات
            المستخدمين.
            <br />
            التكنولوجيا وراء تلك المنصات و خصوصاً فيما يتعلق بالأجهزة الذكية
            نقوم بتوفير بعضها باستخدام Flutter و الذي بدورة يوفر اداء فعال و
            يساهم في رفع معدلات الانجاز في والوقت ذاته.
            <br />
            حيث ان Flutter يعتبر افضل منصات ال Cross-Platform Apps الموجودة
            حالياً من حيث الأداء و الجودة.
            <br /><br />
            اما فيما يخص تطبيقات الطلبة و اولياء الأمور فنظراً لكونها تطبيقات
            عملاقة فلابد من استخدام لغاتها الاصلية لتوفير افضل اداء و هم Swift
            لتطبيقات آبل و Kotlin لتطبيقات آندرويد.
            <br /><br />
            و فيما يخص تطبيقات ال Web فسنستخدم في ذلك المنصة الأسرع على الإطلاق
            و هي Vue مما سيساهم في توفير منتج سريع في وقت اقل.
            <br /><br />
          </p>

          <h1 class="dis-2 text-center">Deployment and Automation</h1>
          <v-row justify="center" align="center">
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="0"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/jenkins.png" />
              <p class="hidden-md-and-up text-center">Jenkins CI/CL</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/git.png" />
              <p class="hidden-md-and-up text-center">Git VC</p>
            </v-col>
            <v-col
              cols="6"
              :md="1"
              :xs="8"
              offset-sm="0"
              offset-md="1"
              style="padding: 30px"
            >
              <v-img src="/imgs/tech/docker.png" />
              <p class="hidden-md-and-up text-center">Docker</p>
            </v-col>
          </v-row>
          <v-row justify="center" align="center" class="hidden-md-and-down">
            <v-col cols="12" :md="1">
              <p class="text-center">Jenkins CI/CL</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center">Git VC</p>
            </v-col>
            <v-col cols="12" :md="1" offset-md="1">
              <p class="text-center">Docker</p>
            </v-col>
          </v-row>
          <p>
            الية العمل و ميكنة عملية النشر تسهل من مهام المطورين و ترفع من كفائة
            و اداء المنصه، حيث انها تضمن ان كل ما سيتم نشره يعمل بكفائة من خلال
            ميكنة عملية الاختبار، كما انه في حالات الطوارئ او الاخطاء الغير
            متوقعه يقوم تلقائياً بالرجوع لأخر نسخة تعمل بكفائة.
          </p>
        </v-container>
      </section>
    </v-main>

    <v-footer class="justify-center" color="#0b0d10" height="100">
      <div
        class="title font-weight-light grey--text text--lighten-1 text-center"
      >
        &copy; {{ new Date().getFullYear() }} — <b>SEBA</b> — Made with 💜 by
        <b style="font-family: monospace" class="pink--text">COC</b>
      </div>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'Index',
  layout: 'seba',
  data() {
    return {
      navColor: 'transparent',
      features: [
        {
          icon: 'mdi-flag-variant',
          title: 'بالنسبة للدولة',
          text: [
            `الرقابة المالية علي الدروس الخصوصية مع توظيف مكاسبها توظيف سليم`,
            `معرفة اجمالي عدد المدرسين الخصوصيين ومعرفة متوسط دخلهم من الدروس`,
            `تقييم المعلمين وتأهيلهم علي نظام التعليم الجديد`,
            `التقييم الفعلي لمستوي الطالب ومعرفة ميولهم واتجاهاتهم والقدرة علي توجيههم للصالح العام`,
            `التحكم في حركة السيولة والنقدية علي المنصة عن طريق جعل جميع الإيداعات تودع في حساب لدي الوزارة له عائد يومي حيث يتم التحصيل من الطلبة مقدما والفع للمدرسين اخر كل شهر`,
          ],
        },
        {
          icon: 'mdi-account-tie',
          title: 'بالنسبة للمعلم',
          text: [
            `زيادة دخل المعلمين عن طريق زيادة عدد الطلاب المشتركين معهم في الدروس الخصوصية`,
            `معرفة نقاط الضعف لديه وطريقة تطويرها وتحسينها`,
            `ربط مستواه التربوي والتعليمي بوظيفته كمدرس تخلق روح تنافسية بين المعلمين مما ينعكس علي انتاجيتهم وتحسين مستوي الطلاب بشكل خاص وتحسين منظومة التعليم بشكل عام`,
          ],
        },
        {
          icon: 'mdi-human-male-child',
          title: 'بالنسبة للطالب والأسرة',
          text: [
            `يستطيع الطالب اختيار المعلم المفضل لديه لكل مادة او انه يجعل التطبيق يقوم بترشيح المعلمين المناسبين له`,
            `يتم تقييم الطالب بشكل دوري للعمل علي تطويره وتحسين نقاط الضعف لديه`,
            `عمل اختبارات الكترونية دورية للطلبة في كل المواد`,
            `مساعدة الأسرة في تربية أبنائهم وفق مناهج تربوية ونفسية مختلفة كل ابن علي حسب شخصيته وميوله ومراحل النمو الخاصة به`,
            `توفير ما يقرب من 50 % من اجمالي مصروفات الاسرة علي الدروس الخصوصية`,
            `يتم ارسال رسائل دورية للأسرة لمعرفة مستوي ابناءهم في كل المواد ومواعيد امتحاناتهم ونتائجهم`,
          ],
        },
      ],
      stats: [
        ['24k', 'Github Stars'],
        ['330+', 'Releases'],
        ['1m', 'Downloads/mo'],
        ['5m', 'Total Downloads'],
      ],
    }
  },
  mounted() {
    this.handleScroll()
    const vm = this
    window.onscroll = (e) => {
      if (window.scrollY > vm.$refs.vid.height) vm.navColor = '#0b0d10'
      else vm.navColor = 'transparent'
    }
  },
  methods: {
    handleScroll() {
      if (window.scrollY > this.$refs.vid.height) this.navColor = '#0b0d10'
      else this.navColor = 'transparent'
    },
    handleVideoEnding() {
      if (window.scrollY > this.$refs.vid.height)
        this.$vuetify.goTo('#about-me')
    },
  },
  head: {
    title: 'SEBA | Educational Plarform',
    meta: [
      { property: 'og:title', content: 'Seba' },
      { property: 'og:description', content: 'Online Education Platform' },
      { property: 'og:img', content: 'https://cocdevs.com/imgs/COC-trans.png' },
    ],
  },
}
</script>
<style lang="css">
*,
html,
body,
h1,
h2,
h3,
h4,
h5,
p {
  font-family: 'Cairo', sans-serif;
}
.cairo-font {
  font-family: 'Cairo', sans-serif !important;
}
.dis-2 {
  font-size: 3rem !important;
  font-weight: 400;
  line-height: 3.125rem;
  letter-spacing: normal !important;
}
.dis-25 {
  font-size: 2.5rem !important;
  font-weight: 400;
  line-height: 3.125rem;
  letter-spacing: normal !important;
}
.dis-3 {
  font-size: 2rem !important;
  font-weight: 400;
  line-height: 3.125rem;
  letter-spacing: normal !important;
}
.theme--dark.v-application {
  background: #000;
}
@font-face {
  font-family: 'Cairo';
  src: url('/fonts/Cairo/Cairo-Regular.ttf');
  font-weight: 250;
  font-style: normal;
}
@font-face {
  font-family: 'Cairo';
  src: url('/fonts/Cairo/Cairo-Bold.ttf');
  font-weight: bold;
  font-style: normal;
}
@font-face {
  font-family: 'Cairo';
  src: url('/fonts/Cairo/Cairo-BoldItalic.ttf');
  font-weight: bold;
  font-style: italic;
}
@font-face {
  font-family: 'Cairo';
  src: url('/fonts/Cairo/Cairo-LightItalic.ttf');
  font-weight: light;
  font-style: italic;
}
@font-face {
  font-family: 'Cairo';
  src: url('/fonts/Cairo/Cairo-Light.ttf');
  font-weight: light;
  font-style: normal;
}
</style>
