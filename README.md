# MOB_Lab-1

1. ZeroButton-ийн аль хоёр байршуулаххязгаарлалтын атрибут нь ZeroButton-г нөгөө хоёр Button элемент хооронд босоо чиглүүлэх зайд оруулах вэ?(2 хариулт уу.)
->**Android:layout_marginBottom="8dp"**
->**Android:layout_marginTop="8dp"**


2. ZeroButton-ийн аль байршуулах хязгаарлалтын атрибут нь бусад хоёр Button элементтэй хэвтээ чиглүүлэх вэ?
->**app:layout_constraintLeft_toLeftOf = "parent**

Харин ямар 2 button өмнө хойно нь байрлахыг доорх 2 тодорхойлно.
app:layout_constraintTop_toBottomOf="@+id/button_toast"
app:layout_constraintBottom_toTopOf="@+id/button_count"

3. Товч дарагдсан үед ажиллах функцийг XML файлд android:onClick атрибут ашиглан тодорхойлсон бол уг функцын жава файлд үүсэх функц нь дараах 4-аас аль нь вэ?"
->**public void callMethod(View view)**


4. Count товчийг дарагдуулах функц нь дараах ажиллаж байгаа үед:
->**Public void countUp(View view)**


5. Count товчны самбарыг өөрчлөхийн тулд дараах 2 арга хэрэгслийг ашиглах боломжтой. туслах аль нь илүү хялбар болгох тайлбарла
->**:view.setBackgroundColor()**

