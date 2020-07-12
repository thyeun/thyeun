const specialist = {
    firstname: "Thomas",
    lastname: "Yeun",
    workingfield: {
        preference: "Semiconductor-AOI",
        regulars: [
            "AOI Process WorkFlow",
            "AOI Equipment WorkFlow",
            "AOI System WorkFlow",
            "AOI Competency WorkFlow",
        ],
        occasional: "AOI software developer"
    },
    contactMe: function() {
        if (needHelp || wannaChat) {
            tweetAt('@thyeun');
        } else {
            return false;
        }
    }
};