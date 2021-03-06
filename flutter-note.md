# Flutter Note

## Lecture Website

- [AppBrewey](https://www.appbrewery.co/courses/flutter-development-bootcamp-with-dart/lectures/9986049)

## Useful Resources

- [Tree Strcture Diagram](https://app.diagrams.net/)
- [App Icon Generator](https://appicon.co/)
- [Free Illustrations](http://icons8.com/ouch)
- [Another Free Illustrations](https://www.vecteezy.com/)
- [Create Your Own](https://www.canva.com/)
- [Flutter Documentation](https://api.flutter.dev/index.html)
- [Flutter Layout Cheat Sheet](https://medium.com/flutter-community/flutter-layout-cheat-sheet-5363348d037e)
- [Free Fonts (for Commercial Use As Well)](https://fonts.google.com/)
- [Color Palette & Icons](https://www.materialpalette.com/)
- [Flutter Package](https://pub.dev/flutter/packages)
- [Material Design (List of Icons and Palette)](https://www.materialpalette.com/icons)
- [Inspiring App Design (Dribble)](https://dribbble.com/)
-[color zillar (allows to pick color code on webpages)](https://chrome.google.com/webstore/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp?hl=en)

## Coding Tips

- Always use a single quote
- 'alt'+'Enter'
- hot reload: stless + 'ctrl + s'
- hot reset: test from start
- `container` without child (ONLY ONE IS ALLOWED): trying to be as big as possible + with child: shrinks to the size of children (such as text)
- `SafeArea`: allows to put everything inside of bumpy designs of phone
- `padding` = inside of container
- `margin` = outside of container
- create a container with infinite length to shift containers to the right
- list of variables(?):'ctrl' + 'q'
- ![image](https://user-images.githubusercontent.com/68700599/89716577-bf2bb300-d973-11ea-849d-8b11a5b5387e.png)
- `stateless` = do not change VS `stateful` = change (has user interaction)


## Learning Tips

- Use Cornell notes
- Use Calendar strike
- Avoid distractions
- Procrastination (미루기) - 공부하기 전에 세팅하고 커피도 마시고 이러는 것보단 (feeding procrastination), 공부를 한 시간 한 후에 커피도 마시고 연필도 깎는 것 (rewarding accomplishment)
- Use another habit to build a new habit - 이미 있는 habit 바로 다음에 해서 (아침에 이 닦은 후 바로 20분동안 무조건 앉아있기 -> 명상하기로) 쉽게 habit을 build 할 수 있는 것
- 딱! 20분만 하자고 하고, 그 이후엔 inertia가 해결해줌. (물론 20분만 해도 20분이나 했으니까 OK!)


## When dart sdk is not configured

File-> Settings (ctrl+alt+s)

Languages and Frameworks -> Dart

Check "Enable Dart support for the project..."

In "Dart SDK path" click in "..." and navigate to flutter SDK directory. Under that directory you'll find **"bin/cache/dart-sdk"**. This is the dart sdk path you should use.

Click "Apply"

Reference: https://stackoverflow.com/questions/48650831/dart-sdk-is-not-configured
