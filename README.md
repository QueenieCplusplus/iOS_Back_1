# iOS_Back_1
ButtonAction &amp; LabelOutlet


    //
    //  ViewController.swift
    //  the StoryBoard's properties named class shall correspond with controller's name
    //  KatesiOSApp2021
    //
    //  Created by KatesAndroid on 2021/1/26.
    //

    import UIKit
    import AVFoundation

    class MainPage: UIViewController {


        @IBOutlet weak var showText: UILabel!



        override func viewDidLoad() {
            super.viewDidLoad()
            // Do any additional setup after loading the view

        }


        @IBAction func onCick(_ sender: Any) {

            showText.text = "I luv mobile app so much, miss you. :)"

        }


    }

2. snapshot.

![](https://raw.githubusercontent.com/QueenieCplusplus/iOS_Back_1/main/before_click.png)
