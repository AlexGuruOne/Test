# Test
 void successfulSearchTest() {
        open("https://www.google.com/");
        $("[name=q]").setValue("selenide1").pressEnter();
        $("[id=search]").shouldHave(text("https://selenide.org"));
    }
}
