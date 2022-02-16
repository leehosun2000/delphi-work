object Form1: TForm1
  Left = 0
  Top = 0
  Caption = 'Initializing browser. Please wait...'
  ClientHeight = 624
  ClientWidth = 1038
  Color = clBtnFace
  Font.Charset = DEFAULT_CHARSET
  Font.Color = clWindowText
  Font.Height = -11
  Font.Name = 'Tahoma'
  Font.Style = []
  OldCreateOrder = False
  Position = poScreenCenter
  OnCloseQuery = FormCloseQuery
  OnCreate = FormCreate
  OnShow = FormShow
  PixelsPerInch = 96
  TextHeight = 13
  object AddressPnl: TPanel
    Left = 0
    Top = 0
    Width = 1038
    Height = 30
    Align = alTop
    BevelOuter = bvNone
    Enabled = False
    Padding.Left = 5
    Padding.Top = 5
    Padding.Right = 5
    Padding.Bottom = 5
    TabOrder = 0
    object AddressEdt: TEdit
      Left = 5
      Top = 5
      Width = 966
      Height = 20
      Margins.Right = 5
      Align = alClient
      TabOrder = 0
      Text = 'https://partners.coupang.com'
      ExplicitHeight = 21
    end
    object GoBtn: TButton
      Left = 1002
      Top = 5
      Width = 31
      Height = 20
      Margins.Left = 5
      Align = alRight
      Caption = 'Go'
      TabOrder = 1
      OnClick = GoBtnClick
    end
    object CpBtn: TButton
      Left = 971
      Top = 5
      Width = 31
      Height = 20
      Margins.Left = 5
      Align = alRight
      Caption = 'CP'
      TabOrder = 2
      OnClick = CpBtnClick
    end
  end
  object CEFWindowParent1: TCEFWindowParent
    Left = 0
    Top = 30
    Width = 1038
    Height = 594
    Align = alClient
    TabOrder = 1
    ExplicitLeft = -8
    ExplicitTop = 31
  end
  object Timer1: TTimer
    Enabled = False
    Interval = 300
    OnTimer = Timer1Timer
    Left = 56
    Top = 88
  end
  object Chromium1: TChromium
    OnTextResultAvailable = Chromium1TextResultAvailable
    OnLoadEnd = Chromium1LoadEnd
    OnAddressChange = Chromium1AddressChange
    OnBeforePopup = Chromium1BeforePopup
    OnAfterCreated = Chromium1AfterCreated
    OnBeforeClose = Chromium1BeforeClose
    OnClose = Chromium1Close
    OnOpenUrlFromTab = Chromium1OpenUrlFromTab
    OnExtensionLoaded = Chromium1ExtensionLoaded
    Left = 56
    Top = 152
  end
  object Timer2: TTimer
    Enabled = False
    OnTimer = Timer2Timer
    Left = 112
    Top = 88
  end
end
