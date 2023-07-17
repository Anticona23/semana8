package com.example.demo;

import org.springframework.stereotype.Controller;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.ResponseBody;

@Controller
public class MainController  {

    @GetMapping(path="/")
    public @ResponseBody String home()
    {
        return "Hello World";
    }
}
