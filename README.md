# iOS_Back_1
ButtonAction &amp; LabelOutlet


1. prepare an Apple ID, Apple Devloper's Account and team_name for Project.


2. install xcode 10+ (for iOS 12 beta later) and use swift version 4+. 
    
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


3. iOS' hot key.

   * UI Object Lib:
    
          cmd + shift + L
       
   * Double View for storyboard and Code:
   
          ctrl + opt + cmd + enter 
          
   * drag UI element on Storyboard as Variable in Code:
   
          two fingers on Mac mouse.
