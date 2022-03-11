
var view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 896)

view.backgroundColor = .white


var shadows = UIView()

shadows.frame = view.frame

shadows.clipsToBounds = false

view.addSubview(shadows)


let shadowPath0 = UIBezierPath(roundedRect: shadows.bounds, cornerRadius: 0)

let layer0 = CALayer()

layer0.shadowPath = shadowPath0.cgPath

layer0.shadowColor = UIColor(red: 0.933, green: 0.933, blue: 0.984, alpha: 1).cgColor

layer0.shadowOpacity = 1

layer0.shadowRadius = 100

layer0.shadowOffset = CGSize(width: 0, height: 6)

layer0.bounds = shadows.bounds

layer0.position = shadows.center

shadows.layer.addSublayer(layer0)


var shapes = UIView()

shapes.frame = view.frame

shapes.clipsToBounds = true

view.addSubview(shapes)


let layer1 = CALayer()

layer1.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor

layer1.bounds = shapes.bounds

layer1.position = shapes.center

shapes.layer.addSublayer(layer1)





// Views / Images: Ratio


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 155, height: 155)

view.backgroundColor = .white


shadows = UIView()

shadows.frame = view.frame

shadows.clipsToBounds = false

view.addSubview(shadows)


let shadowPath0 = UIBezierPath(roundedRect: shadows.bounds, cornerRadius: 0)

let layer0 = CALayer()

layer0.shadowPath = shadowPath0.cgPath

layer0.shadowColor = UIColor(red: 0.608, green: 0.608, blue: 0.608, alpha: 0.13).cgColor

layer0.shadowOpacity = 1

layer0.shadowRadius = 4

layer0.shadowOffset = CGSize(width: 0, height: 2)

layer0.bounds = shadows.bounds

layer0.position = shadows.center

shadows.layer.addSublayer(layer0)





// Frame 33844


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 896)

view.backgroundColor = .white





// Register (step 1)


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 896)

view.backgroundColor = .white


view.layer.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor




// Screen_2


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 896)

view.backgroundColor = .white


view.layer.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor




// Game (step 1)


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 896)

view.backgroundColor = .white


view.layer.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor




// Game (step 1)


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 896)

view.backgroundColor = .white


view.layer.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor




// Game (step 1)


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 896)

view.backgroundColor = .white


view.layer.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor




// Register (step 1)


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 896)

view.backgroundColor = .white


view.layer.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor




// Profile....


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 428, height: 896)

view.backgroundColor = .white


view.layer.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor




// Follow


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 63, height: 22)

view.backgroundColor = .white


view.textColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1)

view.font = UIFont(name: "Roboto-Bold", size: 20)


// Line height: 23 pt


view.attributedText = NSMutableAttributedString(string: "Follow", attributes: [NSAttributedString.Key.kern: 0.8])




// Home 


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 896)

view.backgroundColor = .white


view.layer.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor




// Home 


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 896)

view.backgroundColor = .white


view.layer.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor




// Views / Images: Ratio


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 160, height: 127)

view.backgroundColor = .white


shadows = UIView()

shadows.frame = view.frame

shadows.clipsToBounds = false

view.addSubview(shadows)


let shadowPath0 = UIBezierPath(roundedRect: shadows.bounds, cornerRadius: 0)

let layer0 = CALayer()

layer0.shadowPath = shadowPath0.cgPath

layer0.shadowColor = UIColor(red: 0.608, green: 0.608, blue: 0.608, alpha: 0.13).cgColor

layer0.shadowOpacity = 1

layer0.shadowRadius = 4

layer0.shadowOffset = CGSize(width: 0, height: 2)

layer0.bounds = shadows.bounds

layer0.position = shadows.center

shadows.layer.addSublayer(layer0)





// Iconly/Light/Plus


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 24, height: 24)

view.backgroundColor = .white





// Native / Status Bar


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 44)

view.backgroundColor = .white


view.layer.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor




// Table View Group


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 350, height: 30)

view.backgroundColor = .white





// Frame 6


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 896.45)

view.backgroundColor = .white


view.layer.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor




// Pebble People Working From Home


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 398, height: 450)

view.backgroundColor = .white


let image0 = UIImage(named: "professional-development-3.jpg")?.cgImage

let layer0 = CALayer()

layer0.contents = image0

layer0.transform = CATransform3DMakeAffineTransform(CGAffineTransform(a: 1, b: 0, c: 0, d: 0.5, tx: 0, ty: 0.25))

layer0.bounds = view.bounds

layer0.position = view.center

view.layer.addSublayer(layer0)





// Events


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 896)

view.backgroundColor = .white


shadows = UIView()

shadows.frame = view.frame

shadows.clipsToBounds = false

view.addSubview(shadows)


let shadowPath0 = UIBezierPath(roundedRect: shadows.bounds, cornerRadius: 0)

let layer0 = CALayer()

layer0.shadowPath = shadowPath0.cgPath

layer0.shadowColor = UIColor(red: 0.933, green: 0.933, blue: 0.984, alpha: 1).cgColor

layer0.shadowOpacity = 1

layer0.shadowRadius = 100

layer0.shadowOffset = CGSize(width: 0, height: 6)

layer0.bounds = shadows.bounds

layer0.position = shadows.center

shadows.layer.addSublayer(layer0)


shapes = UIView()

shapes.frame = view.frame

shapes.clipsToBounds = true

view.addSubview(shapes)


let layer1 = CALayer()

layer1.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor

layer1.bounds = shapes.bounds

layer1.position = shapes.center

shapes.layer.addSublayer(layer1)





// Native / Status Bar


view = UILabel()

view.frame = CGRect(x: 0, y: 0, width: 414, height: 44)

view.backgroundColor = .white


view.layer.backgroundColor = UIColor(red: 1, green: 1, blue: 1, alpha: 1).cgColor
