import UIKit
import MediaPlayer
//import AVKit
class ViewController: UIViewController {


    var pc:MPMoviePlayerViewController!

//    var pc:AVPlayerViewController!
    @IBAction func playVideobtn(sender: AnyObject) {
        //添加一个视频文件"2.mp4"
        pc = MPMoviePlayerViewController(contentURL: NSBundle.mainBundle().URLForResource("2", withExtension: "mp4"))

        presentViewController(pc, animated: true, completion: nil)
    }

    override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view, typically from a nib.
    }

    override func didReceiveMemoryWarning() {
        super.didReceiveMemoryWarning()
        // Dispose of any resources that can be recreated.
    }


}
