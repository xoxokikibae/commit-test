# commit-test
It's 2nd test version
//FAQ 글 전체 한 눈에 보는 화면
    @GetMapping("/showAllFaq")

    //FAQ 글 작성 화면
    @GetMapping("/faqForm")


    @GetMapping

    //FAQ 글 id값으로 상세 보기
    @GetMapping("showOne/{id}")
    public String show (@PathVariable Long id, Model model) {
        model.addAttribute("FAQ");

        //댓글
    }
